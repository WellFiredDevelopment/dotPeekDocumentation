.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_personaldataversionupdater:

PersonalDataVersionUpdater
===========================

**Namespace:** :ref:`WellFired.Peek.ViewModel.DataStorage<namespacewellfired_peek_viewmodel_datastorage>`

Description
------------



Properties
-----------

+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|abstract int   |:ref:`VersionNo<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_personaldataversionupdater_1a72a24fce20f770090d2aa1c747d52d8b>` **{** get; set; **}**   |
+---------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Public Static Methods
----------------------

+---------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|IEnumerable< IVersionUpdater >   |:ref:`GetVersionUpdaters<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_personaldataversionupdater_1a9bbceca09706747ab20fbe711c9a1021>` **(** IDataStorageService dataStorageService **)**   |
+---------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|int                              |:ref:`GetLastVersion<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_personaldataversionupdater_1ab0f99af24014cb040ea7a975bf9b1dc4>` **(**  **)**                                             |
+---------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

protected-func
---------------

+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|             |:ref:`PersonalDataVersionUpdater<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_personaldataversionupdater_1aba1daf7ae55ba3197de1021023c8e91c>` **(** ISerializer serializer, IDataStorageService storageService **)**   |
+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|void         |:ref:`UpdateVersionFile<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_personaldataversionupdater_1a104e4d8273029791675ecc5a017014be>` **(**  **)**                                                                      |
+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Public Methods
---------------

+----------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|bool            |:ref:`IsCompatibleWithCurrentVersion<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_personaldataversionupdater_1ac208dce05f4a3db9e6a9e56d91edf578>` **(**  **)**   |
+----------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|abstract void   |:ref:`UpdatePreviousVersion<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_personaldataversionupdater_1ab1f5a50c3fbba2bf166eebf19beca85c>` **(**  **)**            |
+----------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Breakdown
----------

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_personaldataversionupdater_1a72a24fce20f770090d2aa1c747d52d8b:

- abstract int **VersionNo** **{** get; set; **}**

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_personaldataversionupdater_1a9bbceca09706747ab20fbe711c9a1021:

- IEnumerable< IVersionUpdater > **GetVersionUpdaters** **(** IDataStorageService dataStorageService **)**

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_personaldataversionupdater_1ab0f99af24014cb040ea7a975bf9b1dc4:

- int **GetLastVersion** **(**  **)**

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_personaldataversionupdater_1aba1daf7ae55ba3197de1021023c8e91c:

-  **PersonalDataVersionUpdater** **(** ISerializer serializer, IDataStorageService storageService **)**

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_personaldataversionupdater_1a104e4d8273029791675ecc5a017014be:

- void **UpdateVersionFile** **(**  **)**

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_personaldataversionupdater_1ac208dce05f4a3db9e6a9e56d91edf578:

- bool **IsCompatibleWithCurrentVersion** **(**  **)**

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_personaldataversionupdater_1ab1f5a50c3fbba2bf166eebf19beca85c:

- abstract void **UpdatePreviousVersion** **(**  **)**

