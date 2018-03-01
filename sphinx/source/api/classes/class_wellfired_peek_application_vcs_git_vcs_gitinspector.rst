.. _classwellfired_peek_application_vcs_git_vcs_gitinspector:

GITInspector
=============

**Namespace:** :ref:`WellFired.Peek.Application.VCS<namespacewellfired_peek_application_vcs>`

**Implements:** :ref:`WellFired.Peek.Application.VCS.IVCSInspector<interfacewellfired_peek_application_vcs_ivcsinspector>`


Description
------------



Public Methods
---------------

+----------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
|bool                                                                        |:ref:`IsRepository<classwellfired_peek_application_vcs_git__vcs_gitinspector_1a873d0c7df8efc1acc2a53a1148c8d59b>` **(** string location **)**        |
+----------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
|:ref:`RepositoryInfo<classwellfired_peek_application_vcs_repositoryinfo>`   |:ref:`GetRepositoryInfo<classwellfired_peek_application_vcs_git__vcs_gitinspector_1ab3fccd0b65b174d1a9f49d1eddc552cc>` **(** string location **)**   |
+----------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+

Breakdown
----------

.. _classwellfired_peek_application_vcs_git__vcs_gitinspector_1a873d0c7df8efc1acc2a53a1148c8d59b:

- bool **IsRepository** **(** string location **)**

    **Description**

        Detect if this :ref:`IVCSInspector<interfacewellfired_peek_application_vcs_ivcsinspector>` is compatible with the :ref:`VCS<namespacewellfired_peek_application_vcs>` used at the location specified. 

    **Parameters**

        +-------------+
        |location     |
        +-------------+
        
.. _classwellfired_peek_application_vcs_git__vcs_gitinspector_1ab3fccd0b65b174d1a9f49d1eddc552cc:

- :ref:`RepositoryInfo<classwellfired_peek_application_vcs_repositoryinfo>` **GetRepositoryInfo** **(** string location **)**

    **Description**

        Get information about the state of the repository at the location specified. 

    **Parameters**

        +-------------+
        |location     |
        +-------------+
        
