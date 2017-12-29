.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater:

PersonalDataVersionUpdater
===========================

**Namespace:** :ref:`WellFired.Peek.ViewModel.DataStorage.PersonalDataVersionUpdaters<namespacewellfired_peek_viewmodel_datastorage_personaldataversionupdaters>`

Description
------------



protected-attrib
-----------------

+------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------+
|readonly string   |:ref:`ProjectGUID<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1aa05cccc8e4b4213637f997cbbad74989>`    |
+------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------+

Properties
-----------

+---------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|abstract int   |:ref:`VersionNo<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1ae8380b0973f0b0f5b5ac6c78bd0208bb>` **{** get; set; **}**   |
+---------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Public Static Methods
----------------------

+---------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|IEnumerable< IVersionUpdater >   |:ref:`GetVersionUpdaters<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1a1a2b15daabf41f478142090d66c373a4>` **(** string projectGUID, IDataStorageService dataStorageService = null **)**   |
+---------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

protected-func
---------------

+-------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|             |:ref:`PersonalDataVersionUpdater<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1a5baea63ccf0c9aedd81760aaa4f362a8>` **(** ISerializer serializer, IDataStorageService storageService, string projectGUID **)**   |
+-------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|void         |:ref:`UpdateVersionFile<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1abeb58323aded3c000192ebee7cbbcb3f>` **(**  **)**                                                                                          |
+-------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Public Methods
---------------

+----------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|bool            |:ref:`IsCompatibleWithCurrentVersion<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1a4580883c1ef15e4ad69e33de75242899>` **(**  **)**   |
+----------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|abstract void   |:ref:`UpdatePreviousVersion<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1ad88efd349df9026eeca5a14407d15d33>` **(**  **)**            |
+----------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Breakdown
----------

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1aa05cccc8e4b4213637f997cbbad74989:

- readonly string **ProjectGUID** 

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1ae8380b0973f0b0f5b5ac6c78bd0208bb:

- abstract int **VersionNo** **{** get; set; **}**

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1a1a2b15daabf41f478142090d66c373a4:

- IEnumerable< IVersionUpdater > **GetVersionUpdaters** **(** string projectGUID, IDataStorageService dataStorageService = null **)**

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1a5baea63ccf0c9aedd81760aaa4f362a8:

-  **PersonalDataVersionUpdater** **(** ISerializer serializer, IDataStorageService storageService, string projectGUID **)**

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1abeb58323aded3c000192ebee7cbbcb3f:

- void **UpdateVersionFile** **(**  **)**

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1a4580883c1ef15e4ad69e33de75242899:

- bool **IsCompatibleWithCurrentVersion** **(**  **)**

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1ad88efd349df9026eeca5a14407d15d33:

- abstract void **UpdatePreviousVersion** **(**  **)**

