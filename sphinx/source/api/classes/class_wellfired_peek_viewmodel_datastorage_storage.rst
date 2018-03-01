.. _classwellfired_peek_viewmodel_datastorage_storage:

Storage
========

**Namespace:** :ref:`WellFired.Peek.ViewModel<namespacewellfired_peek_viewmodel>`

**Implements:** :ref:`WellFired.Peek.ViewModel.DataStorage.IStorage<interfacewellfired_peek_viewmodel_datastorage_istorage>`


Description
------------

:ref:`Storage<classwellfired_peek_viewmodel_datastorage_storage>` gives access to the .:ref:`Peek<namespacewellfired_peek>` application data on the disk. :ref:`Save<classwellfired_peek_viewmodel_datastorage_storage_1a275f4d8dfa9f3de4d2a660d283ff3854>` should be called whenever data was modified. 

Properties
-----------

+--------------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------+
|:ref:`OptionsProxy<classwellfired_peek_viewmodel_datastorage_dataproxies_optionsproxy>`           |:ref:`PersonalOptions<classwellfired_peek_viewmodel_datastorage_storage_1ac4d8c3a420a4ecd6d8da614207aa050a>` **{** get; set; **}**            |
+--------------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------+
|:ref:`TeamOptionsProxy<classwellfired_peek_viewmodel_datastorage_dataproxies_teamoptionsproxy>`   |:ref:`TeamOptions<classwellfired_peek_viewmodel_datastorage_storage_1aca4a39abe43789ef386d57a67dfcb3e8>` **{** get; set; **}**                |
+--------------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------+
|:ref:`ProjectInfoProxy<classwellfired_peek_viewmodel_datastorage_dataproxies_projectinfoproxy>`   |:ref:`ProjectInfo<classwellfired_peek_viewmodel_datastorage_storage_1a5bbbc805a7a82899d6aaf3f48ea68dad>` **{** get; set; **}**                |
+--------------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------+
|string                                                                                            |:ref:`BuildReportsAbsolutePath<classwellfired_peek_viewmodel_datastorage_storage_1aff927162bdd3bd863d08f0f5067afe19>` **{** get; set; **}**   |
+--------------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------+

Public Methods
---------------

+-------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
|void         |:ref:`Initialize<classwellfired_peek_viewmodel_datastorage_storage_1ae3aa203a1ef0a579a4a81f6c26ee509b>` **(** IPlatformProvider platformProvider **)**   |
+-------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
|void         |:ref:`Save<classwellfired_peek_viewmodel_datastorage_storage_1a275f4d8dfa9f3de4d2a660d283ff3854>` **(**  **)**                                           |
+-------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+

Breakdown
----------

.. _classwellfired_peek_viewmodel_datastorage_storage_1ac4d8c3a420a4ecd6d8da614207aa050a:

- :ref:`OptionsProxy<classwellfired_peek_viewmodel_datastorage_dataproxies_optionsproxy>` **PersonalOptions** **{** get; set; **}**

    **Description**

        This stores the personal options of the user which are only visible from its computer and should not be commited to VCS. This is located in "[Project]/.wellfired" 

.. _classwellfired_peek_viewmodel_datastorage_storage_1aca4a39abe43789ef386d57a67dfcb3e8:

- :ref:`TeamOptionsProxy<classwellfired_peek_viewmodel_datastorage_dataproxies_teamoptionsproxy>` **TeamOptions** **{** get; set; **}**

    **Description**

        This stores the team-shared options of the project. This should be commited to your VCS. This is located in "[Project]/WellFired" 

.. _classwellfired_peek_viewmodel_datastorage_storage_1a5bbbc805a7a82899d6aaf3f48ea68dad:

- :ref:`ProjectInfoProxy<classwellfired_peek_viewmodel_datastorage_dataproxies_projectinfoproxy>` **ProjectInfo** **{** get; set; **}**

    **Description**

        This stores information about the project accross the different users. This is also stored in [Project]/WellFired and should be commited on the VCS. 

.. _classwellfired_peek_viewmodel_datastorage_storage_1aff927162bdd3bd863d08f0f5067afe19:

- string **BuildReportsAbsolutePath** **{** get; set; **}**

    **Description**

        Where the build report is currently being saved. This is an absolute path. 

.. _classwellfired_peek_viewmodel_datastorage_storage_1ae3aa203a1ef0a579a4a81f6c26ee509b:

- void **Initialize** **(** IPlatformProvider platformProvider **)**

    **Description**

        Initialize the storage with the tools specific to the platform it is being initialized on (:ref:`Unity<namespacewellfired_peek_unity>`, Unreal, etc...) 

    **Parameters**

        +-------------------+
        |platformProvider   |
        +-------------------+
        
.. _classwellfired_peek_viewmodel_datastorage_storage_1a275f4d8dfa9f3de4d2a660d283ff3854:

- void **Save** **(**  **)**

    **Description**

        Save all the modifications done to modified settings (:ref:`TeamOptions<classwellfired_peek_viewmodel_datastorage_storage_1aca4a39abe43789ef386d57a67dfcb3e8>`, :ref:`PersonalOptions<classwellfired_peek_viewmodel_datastorage_storage_1ac4d8c3a420a4ecd6d8da614207aa050a>`, ...). 

