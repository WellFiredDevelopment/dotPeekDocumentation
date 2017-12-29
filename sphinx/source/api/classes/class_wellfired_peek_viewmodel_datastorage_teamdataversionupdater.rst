.. _classwellfired_peek_viewmodel_datastorage_teamdataversionupdater:

TeamDataVersionUpdater
=======================

**Namespace:** :ref:`WellFired.Peek.ViewModel<namespacewellfired_peek_viewmodel>`

Description
------------



Properties
-----------

+---------------+----------------------------------------------------------------------------------------------------------------------------------------------+
|abstract int   |:ref:`VersionNo<classwellfired_peek_viewmodel_datastorage_teamdataversionupdater_1ac0e6f44ed6fe274901239a49e43be402>` **{** get; set; **}**   |
+---------------+----------------------------------------------------------------------------------------------------------------------------------------------+

Public Static Methods
----------------------

+---------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|IEnumerable< IVersionUpdater >   |:ref:`GetVersionUpdaters<classwellfired_peek_viewmodel_datastorage_teamdataversionupdater_1af3ba6a6a7a76f4a4da9d421aadee2a8d>` **(** IDataStorageService dataStorageService = null **)**   |
+---------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

protected-func
---------------

+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|             |:ref:`TeamDataVersionUpdater<classwellfired_peek_viewmodel_datastorage_teamdataversionupdater_1aed8f868b26ca867d742e8c209f965a59>` **(** ISerializer serializer, IDataStorageService storageService **)**   |
+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|void         |:ref:`UpdateVersionFile<classwellfired_peek_viewmodel_datastorage_teamdataversionupdater_1a20a3c73c76c7c32797c30d902060aa6a>` **(**  **)**                                                                  |
+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Public Methods
---------------

+----------------+----------------------------------------------------------------------------------------------------------------------------------------------------------+
|bool            |:ref:`IsCompatibleWithCurrentVersion<classwellfired_peek_viewmodel_datastorage_teamdataversionupdater_1a6b0fd3f021c31981c4f5ef3222fc39ef>` **(**  **)**   |
+----------------+----------------------------------------------------------------------------------------------------------------------------------------------------------+
|abstract void   |:ref:`UpdatePreviousVersion<classwellfired_peek_viewmodel_datastorage_teamdataversionupdater_1a0603e30c7e42f8b5443fa35ad8e2729b>` **(**  **)**            |
+----------------+----------------------------------------------------------------------------------------------------------------------------------------------------------+

Breakdown
----------

.. _classwellfired_peek_viewmodel_datastorage_teamdataversionupdater_1ac0e6f44ed6fe274901239a49e43be402:

- abstract int **VersionNo** **{** get; set; **}**

.. _classwellfired_peek_viewmodel_datastorage_teamdataversionupdater_1af3ba6a6a7a76f4a4da9d421aadee2a8d:

- IEnumerable< IVersionUpdater > **GetVersionUpdaters** **(** IDataStorageService dataStorageService = null **)**

.. _classwellfired_peek_viewmodel_datastorage_teamdataversionupdater_1aed8f868b26ca867d742e8c209f965a59:

-  **TeamDataVersionUpdater** **(** ISerializer serializer, IDataStorageService storageService **)**

.. _classwellfired_peek_viewmodel_datastorage_teamdataversionupdater_1a20a3c73c76c7c32797c30d902060aa6a:

- void **UpdateVersionFile** **(**  **)**

.. _classwellfired_peek_viewmodel_datastorage_teamdataversionupdater_1a6b0fd3f021c31981c4f5ef3222fc39ef:

- bool **IsCompatibleWithCurrentVersion** **(**  **)**

.. _classwellfired_peek_viewmodel_datastorage_teamdataversionupdater_1a0603e30c7e42f8b5443fa35ad8e2729b:

- abstract void **UpdatePreviousVersion** **(**  **)**

