.. _interfacewellfired_peek_application_vcs_ivcsinspector:

IVCSInspector
==============

**Namespace:** :ref:`WellFired.Peek.Application<namespacewellfired_peek_application>`

Description
------------

Utility tool to get information about a specific :ref:`VCS<namespacewellfired_peek_application_vcs>`

Public Methods
---------------

+----------------------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
|bool                                                                        |:ref:`IsRepository<interfacewellfired_peek_application_vcs_ivcsinspector_1a1cc81c1f8356b9b58f384784091ff61c>` **(** string location **)**        |
+----------------------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
|:ref:`RepositoryInfo<classwellfired_peek_application_vcs_repositoryinfo>`   |:ref:`GetRepositoryInfo<interfacewellfired_peek_application_vcs_ivcsinspector_1a9f284aa87adfb9522193678ce0ca5479>` **(** string location **)**   |
+----------------------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+

Breakdown
----------

.. _interfacewellfired_peek_application_vcs_ivcsinspector_1a1cc81c1f8356b9b58f384784091ff61c:

- bool **IsRepository** **(** string location **)**

    **Description**

        Detect if this :ref:`IVCSInspector<interfacewellfired_peek_application_vcs_ivcsinspector>` is compatible with the :ref:`VCS<namespacewellfired_peek_application_vcs>` used at the location specified. 

    **Parameters**

        +-------------+
        |location     |
        +-------------+
        
.. _interfacewellfired_peek_application_vcs_ivcsinspector_1a9f284aa87adfb9522193678ce0ca5479:

- :ref:`RepositoryInfo<classwellfired_peek_application_vcs_repositoryinfo>` **GetRepositoryInfo** **(** string location **)**

    **Description**

        Get information about the state of the repository at the location specified. 

    **Parameters**

        +-------------+
        |location     |
        +-------------+
        
