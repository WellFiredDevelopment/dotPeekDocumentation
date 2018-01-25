.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater:

PersonalDataVersionUpdater
===========================

**Namespace:** :ref:`WellFired.Peek.ViewModel.DataStorage.PersonalDataVersionUpdaters<namespacewellfired_peek_viewmodel_datastorage_personaldataversionupdaters>`

Description
------------



Properties
-----------

+---------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|abstract int   |:ref:`VersionNo<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1ae8380b0973f0b0f5b5ac6c78bd0208bb>` **{** get; set; **}**   |
+---------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Public Static Methods
----------------------

+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|IEnumerable< IVersionUpdater >   |:ref:`GetVersionUpdaters<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1ad17a67c8fffe221a68d761b3392b426e>` **(** IDataStorageService dataStorageService **)**   |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|int                              |:ref:`GetLastVersion<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1a2f9fbe8b95ae5bdf9d59881f4e10a9bf>` **(**  **)**                                             |
+---------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

protected-func
---------------

+-------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|             |:ref:`PersonalDataVersionUpdater<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1ad51f1feba08ace9f737754ab1406a56b>` **(** ISerializer serializer, IDataStorageService storageService **)**   |
+-------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|void         |:ref:`UpdateVersionFile<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1abeb58323aded3c000192ebee7cbbcb3f>` **(**  **)**                                                                      |
+-------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Public Methods
---------------

+----------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|bool            |:ref:`IsCompatibleWithCurrentVersion<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1a4580883c1ef15e4ad69e33de75242899>` **(**  **)**   |
+----------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|abstract void   |:ref:`UpdatePreviousVersion<classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1ad88efd349df9026eeca5a14407d15d33>` **(**  **)**            |
+----------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Breakdown
----------

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1ae8380b0973f0b0f5b5ac6c78bd0208bb:

- abstract int **VersionNo** **{** get; set; **}**

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1ad17a67c8fffe221a68d761b3392b426e:

- IEnumerable< IVersionUpdater > **GetVersionUpdaters** **(** IDataStorageService dataStorageService **)**

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1a2f9fbe8b95ae5bdf9d59881f4e10a9bf:

- int **GetLastVersion** **(**  **)**

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1ad51f1feba08ace9f737754ab1406a56b:

-  **PersonalDataVersionUpdater** **(** ISerializer serializer, IDataStorageService storageService **)**

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1abeb58323aded3c000192ebee7cbbcb3f:

- void **UpdateVersionFile** **(**  **)**

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1a4580883c1ef15e4ad69e33de75242899:

- bool **IsCompatibleWithCurrentVersion** **(**  **)**

.. _classwellfired_peek_viewmodel_datastorage_personaldataversionupdaters_cs_personaldataversionupdater_1ad88efd349df9026eeca5a14407d15d33:

- abstract void **UpdatePreviousVersion** **(**  **)**

