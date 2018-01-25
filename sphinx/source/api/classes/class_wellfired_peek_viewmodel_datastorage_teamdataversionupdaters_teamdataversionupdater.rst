.. _classwellfired_peek_viewmodel_datastorage_teamdataversionupdaters_teamdataversionupdater:

TeamDataVersionUpdater
=======================

**Namespace:** :ref:`WellFired.Peek.ViewModel.DataStorage<namespacewellfired_peek_viewmodel_datastorage>`

Description
------------



Properties
-----------

+---------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|abstract int   |:ref:`VersionNo<classwellfired_peek_viewmodel_datastorage_teamdataversionupdaters_teamdataversionupdater_1a26757467ef6248c98905d9c5546488fe>` **{** get; set; **}**   |
+---------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Public Static Methods
----------------------

+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|IEnumerable< IVersionUpdater >   |:ref:`GetVersionUpdaters<classwellfired_peek_viewmodel_datastorage_teamdataversionupdaters_teamdataversionupdater_1a118971567dc6a44097a9ee9c5d4ef501>` **(** IDataStorageService dataStorageService **)**   |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|int                              |:ref:`GetLastVersion<classwellfired_peek_viewmodel_datastorage_teamdataversionupdaters_teamdataversionupdater_1ae446d3e44dd6245a5b58a3077bba190b>` **(**  **)**                                             |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

protected-func
---------------

+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|             |:ref:`TeamDataVersionUpdater<classwellfired_peek_viewmodel_datastorage_teamdataversionupdaters_teamdataversionupdater_1a2447b0535236aae015a336e51d7b3bf4>` **(** ISerializer serializer, IDataStorageService storageService **)**   |
+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|void         |:ref:`UpdateVersionFile<classwellfired_peek_viewmodel_datastorage_teamdataversionupdaters_teamdataversionupdater_1a04585561f2b3dee22afb0be9af9dde2f>` **(**  **)**                                                                  |
+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Public Methods
---------------

+----------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|bool            |:ref:`IsCompatibleWithCurrentVersion<classwellfired_peek_viewmodel_datastorage_teamdataversionupdaters_teamdataversionupdater_1a9106cc84c1c1ce4bc2052efb667246a0>` **(**  **)**   |
+----------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|abstract void   |:ref:`UpdatePreviousVersion<classwellfired_peek_viewmodel_datastorage_teamdataversionupdaters_teamdataversionupdater_1a4c9c8a95956e796f375099b998f82ac6>` **(**  **)**            |
+----------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Breakdown
----------

.. _classwellfired_peek_viewmodel_datastorage_teamdataversionupdaters_teamdataversionupdater_1a26757467ef6248c98905d9c5546488fe:

- abstract int **VersionNo** **{** get; set; **}**

.. _classwellfired_peek_viewmodel_datastorage_teamdataversionupdaters_teamdataversionupdater_1a118971567dc6a44097a9ee9c5d4ef501:

- IEnumerable< IVersionUpdater > **GetVersionUpdaters** **(** IDataStorageService dataStorageService **)**

.. _classwellfired_peek_viewmodel_datastorage_teamdataversionupdaters_teamdataversionupdater_1ae446d3e44dd6245a5b58a3077bba190b:

- int **GetLastVersion** **(**  **)**

.. _classwellfired_peek_viewmodel_datastorage_teamdataversionupdaters_teamdataversionupdater_1a2447b0535236aae015a336e51d7b3bf4:

-  **TeamDataVersionUpdater** **(** ISerializer serializer, IDataStorageService storageService **)**

.. _classwellfired_peek_viewmodel_datastorage_teamdataversionupdaters_teamdataversionupdater_1a04585561f2b3dee22afb0be9af9dde2f:

- void **UpdateVersionFile** **(**  **)**

.. _classwellfired_peek_viewmodel_datastorage_teamdataversionupdaters_teamdataversionupdater_1a9106cc84c1c1ce4bc2052efb667246a0:

- bool **IsCompatibleWithCurrentVersion** **(**  **)**

.. _classwellfired_peek_viewmodel_datastorage_teamdataversionupdaters_teamdataversionupdater_1a4c9c8a95956e796f375099b998f82ac6:

- abstract void **UpdatePreviousVersion** **(**  **)**

