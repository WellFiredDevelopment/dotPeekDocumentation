Continuous Integration
======================

.Peek was designed to provide a quick feedback to Unity users about the status of their project, but also to be nicely integrated
on any Continuous Integration pipeline.

Through the :ref:`doc_advanced_programmatic-control` of DotPeek, you can ensure that your CI run .DotPeek with consistant settings.

Hereunder are more ways of optimizing .Peek usage on a CI machine.

Getting informed when build report is ready
-------------------------------------------

For optimized performances, .Peek generate your build report on threads. It means that when you call Unity on the command line,
you should not do it with the parameter `-quit`. This would quit the editor as soon as the Unity editor main thread finished 
the task it was assigned on the command line.

To allow you to quit unity after the report was generated, .Peek provides you the interface `IDotPeekListener`. You first need
to implement it :

.. code-block:: c#

            private class DotPeekListener : IDotPeekListener
            {
                public void DoBuildReportGenerated(string reportAbsolutePath)
                {
                    //do here what you want after the build is generated
                }
            }

And then to provide this listener to .Peek :

.. code-block:: c#

            DotPeek.Listener = new DotPeekListener();	

Below is a whole functional usage example :

.. code-block:: c#

        using UnityEditor;
        using WellFired.Peek.Application.Unity.Editor;

        [InitializeOnLoad]
        public static class DotPeekInitializer 
        {
            static DotPeekInitializer()
            {
                DotPeek.Listener = new DotPeekListener();		
            }

            private class DotPeekListener : IDotPeekListener
            {
                public void DoBuildReportGenerated(string reportAbsolutePath)
                {
                    //Will quit Unity with error code 0, indicating no error happened.
                    EditorApplication.Exit(0);
                }
            }
        }

The parameter ``reportAbsolutePath`` is the path to your freshly generated report. It can be useful if you want to send the report 
to an other machine for example (website server, NAS, ...)

VCS Version
-----------

If .Peek option is enabled and your project versions are tracked through GIT or SVN, the commid id at build time will be
automatically saved with your generated report. This is done through the terminal of your machine. 

If for any reason .Peek cannot access the terminal of the machine it is running on, you can provide an implementation of 
``IVCS`` and return to .Peek the value you want :

    .. code-block:: c#

        private interface IVCS
        {
            string GetCommitId();
        }

This can be useful for example if the access to the commit id can be done only through the parameters passed to Unity through
the command line. Here an illustration :

The command being called :

    .. code-block:: c#

        /Applications/Unity/Unity.app/Contents/MacOS/Unity -VCS aa2e32w -batchmode -executeMethod MyEditorScript.PerformBuild

The implementation of the static function being called in Unity :

    .. code-block:: c#

        using UnityEditor;
        class MyEditorScript
        {
            static void PerformBuild ()
            {
                DotPeek.CustomVCS = new DotPeekVCS();

                string[] scenes = { "Assets/MyScene.unity" };
                BuildPipeline.BuildPlayer(scenes, ...);
            }
        }

    with ``DotPeekVCS`` implemented this way :

    .. code-block:: c#

        private class DotPeekVCS : IVCS
        {
            public string GetCommitId()
            {
                var args = Environment.GetCommandLineArgs().ToList();
                var optionPosition = args.IndexOf("-VCS");
                var vcsCommitId = args[optionPosition + 1];
                
                return vcsCommitId;
            }
        }
