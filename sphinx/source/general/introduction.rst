.. _doc_general_introduction:

Introduction
============

This page aims at giving a broad presentation of the tool and of the contents of this documentation, so that you know where to start if you are a beginner or where to look if you need info on a specific feature.

About .Peek
-----------

Most of Unity projects requires a large amount of assets (textures, audio files, prefabs, plugins…). These assets have a direct impact on the 
size of your build and the performance of your game. Tracking these assets to ensure your project stays up to quality standards 
and does not become a nightmare to maintain is very hard, especially when you are working in a team of people with different background.

.Peek is here to support you in quickly identifying the usual suspect, before it becomes a real problem. It is a must have for 
any development team who wants to control what goes into their build and react on time when undesirable assets are integrated to 
the project.

Here a list of the core features :

* Provides a list of used and unused assets and their imported size for each builds.
* Automatically generate and archive a build report each time a build is performed.
* Provide a nice interface to quickly jump between build reports.
* Selecting two build reports will automatically display a diff of what changed between the two builds.
* Provide the possibility to share build reports on a VCS, or to save it in different location for each team member.
* Possibility to run build generation silently or to totally shut it off.
* Very responsive UI, even for projects with a large amount of assets, thanks to the usage of `.Guacamole <https://github.com/ArtOfSettling/.Guacamole>`_, 
  an open source MVVM framework for Unity.

About the documentation
-----------------------

This documentation is continuously written, corrected, edited and revamped by members of the .Peek team and
community. It is edited via text files in the `reStructuredText <http://www.sphinx-doc.org/en/stable/rest.html>`_ markup
language and then compiled into a static website/offline document using the open source
`Sphinx <http://www.sphinx-doc.org>`_ and `ReadTheDocs <https://readthedocs.org/>`_ tools.

.. note:: You can contribute to .Peek's documentation by opening issues through
            `YouTrack <https://wellfired.myjetbrains.com/youtrack/issues/DPeek>`_
            or sending patches via pull requests on its GitHub
            `source repository <https://github.com/WellFiredDevelopment/dotPeekDocumentation>`_.

Organisation of the documentation
---------------------------------

This documentation is organised in five sections, the way it is split up should be relatively intuitive:

- The :ref:`sec-general` section contains this introduction as well as the :ref:`doc_general_faq`.
- The :ref:`sec-getting-started` section gives you a quick entry point to start using the tool.
- Finally, the :ref:`sec-class-ref` is the documentation of the .Peek API. It is generated automatically from files in the 
  main repository, and the generated files of the documentation are therefore not meant to be modified.
