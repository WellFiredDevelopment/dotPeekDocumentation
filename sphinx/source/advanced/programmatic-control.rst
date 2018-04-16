.. _doc_advanced_programmatic-control:

Programmatic Control
====================

Settings
--------

All the settings you can access through .Peek UI are available through code and can be read or overwritten.

To do so :

1. Add the required using :

.. code-block:: c#

        using WellFired.Peek.Application.Unity.Editor;

2. Access and modify your .Peek personal options (stored on your computer only, see :ref:`doc_ui-overview_settings-page` for more information) :

.. code-block:: c#

        DotPeek.Storage.PersonalOptions.BuildReportPath = "../DotPeekReports";
        DotPeek.Storage.PersonalOptions.AutomaticallyShowReportAfterBuild = false;

3. Access and modify your .Peek team-shared options :

.. code-block:: c#

        DotPeek.Storage.TeamOptions.TrackVCSVersion = false;

4. Save your changes to ensure .Peek can access updated settings :

.. code-block:: c#

        DotPeek.Storage.Save();

.. warning:: Saving step cannot be ommited. Indeed, it will ensure settings that were modified are written to the disk and
   are accessible to the whole .Peek application.

.. tip:: .Peek Storage is thread safe, so the thread you are accessing it from does not matter.

Callbacks Order
---------------

DotPeek build generation is driven by two callbacks automatically called by Unity when building :

* `IPreprocessBuild.OnPreprocessBuild <https://docs.unity3d.com/ScriptReference/Build.IPreprocessBuild.html>`_ which happens just
  before the build starts.

  When it is called, .Peek will start counting the time used to build and get the VCS commit ID of your project.
  Note that if beforehand some files were not commited, .Peek will add *-unsync* behind the commit ID.
  
  |

* `IPostprocessBuild.OnPostprocessBuild <https://docs.unity3d.com/ScriptReference/Build.IPostprocessBuild.html>`_ which is 
  called once the build is done.
  
  When it is called, the time elapsed to make the build is saved and the report generated. Note that at that moment, 
  all the files that are in the project, but were not added to the build are considered as unused assets.

Different modules in your project may use these callbacks, and Unity will decide which one to call first based on
`IPreprocessBuild.callbackOrder and IPostprocessBuild.callbackOrder <https://docs.unity3d.com/ScriptReference/Build.IOrderedCallback.html>`_

.Peek by default try to be called as early as possible and as late as possible, but you can programmatically change this
behaviour by :

1. Adding the required using :

.. code-block:: c#

        using WellFired.Peek.Application.Unity.Editor;

2. Modifying the callback order :

.. code-block:: c#

        DotPeek.Storage.TeamOptions.PrebuildCallbackOrder = int.MinValue + 1;
        DotPeek.Storage.TeamOptions.PostbuildCallbackOrder = int.MaxValue - 1;

4. Saving your changes to ensure .Peek can access updated settings :

.. code-block:: c#

        DotPeek.Storage.Save();

Manually start .Peek metric counters
-------------------------------------

There is some situations you might not want to rely on the `IPreprocessBuild.OnPreprocessBuild <https://docs.unity3d.com/ScriptReference/Build.IPreprocessBuild.html>`_.

Indeed, when this Unity callback is called, .Peek will check your VCS status and starts counting how much time
your build takes. 

If ever your build pipeline is based on a custom script that executes some operations before Unity
`BuildPipeline.BuildPlayer <https://docs.unity3d.com/ScriptReference/BuildPipeline.BuildPlayer.html>`_ is called, then
when OnPreprocessBuild is called, your VCS may already have some local changes, or your build may already have taken
several minutes, which will lead .Peek to display wrong information at the end of the build.

To avoid this situation you can force .Peek to start tracking these information before BuildPipeline.BuildPlayer is called. Here the steps :

1. Add the required using :

.. code-block:: c#

        using WellFired.Peek.Application.Unity.Editor;

2. Start .Peek session with the Unity build target you are building for :

.. code-block:: c#

        DotPeek.StartSession(BuildTarget.Android);

That's it !