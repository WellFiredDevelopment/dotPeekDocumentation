.. _classwellfired_peek_application_unity_editor_dotpeek:

DotPeek
========

**Namespace:** :ref:`WellFired.Peek.Application.Unity<namespacewellfired_peek_application_unity>`

**Implements:** :ref:`WellFired.Peek.Application.IDotPeekSessionListener<interfacewellfired_peek_application_idotpeeksessionlistener>`


Description
------------

This is a public wrapper around .:ref:`Peek<namespacewellfired_peek>` application. It gives access to different utilities allowing a total control of .:ref:`Peek<namespacewellfired_peek>`. 

Properties
-----------

+---------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------+
|:ref:`IDotPeekListener<interfacewellfired_peek_application_unity_editor_idotpeeklistener>`   |:ref:`Listener<classwellfired_peek_application_unity_editor_dotpeek_1a6019ed665b7d0f4fa95065eaed9fc2dd>` **{** get; set; **}**    |
+---------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------+
|:ref:`IVCS<interfacewellfired_peek_application_vcs_ivcs>`                                    |:ref:`CustomVCS<classwellfired_peek_application_unity_editor_dotpeek_1a381e1d91dc2dff79988fbc20fa60f8bc>` **{** get; set; **}**   |
+---------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------+
|:ref:`Storage<classwellfired_peek_viewmodel_datastorage_storage>`                            |:ref:`Storage<classwellfired_peek_application_unity_editor_dotpeek_1a6a07d42db1939a49cee805130f110e30>` **{** get; set; **}**     |
+---------------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------+

public-static-attrib
---------------------

+------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------+
|bool                                                                          |:ref:`SessionStarted<classwellfired_peek_application_unity_editor_dotpeek_1abe564db373361aee6b238e2ad0656b3f>`    |
+------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------+
|:ref:`IDotPeekSession<interfacewellfired_peek_application_idotpeeksession>`   |:ref:`CurrentSession<classwellfired_peek_application_unity_editor_dotpeek_1aff402afdbd83366fbb04d443196f51c9>`    |
+------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------+

Public Static Methods
----------------------

+-------------+----------------------------------------------------------------------------------------------------------------------------------------------+
|void         |:ref:`StartSession<classwellfired_peek_application_unity_editor_dotpeek_1a379f2a1a6f056f71713c8db132af2d1d>` **(** BuildTarget target **)**   |
+-------------+----------------------------------------------------------------------------------------------------------------------------------------------+
|void         |:ref:`EndSession<classwellfired_peek_application_unity_editor_dotpeek_1ad76db20c5995cfda9224e4413113ce84>` **(**  **)**                       |
+-------------+----------------------------------------------------------------------------------------------------------------------------------------------+
|void         |:ref:`OpenWindow<classwellfired_peek_application_unity_editor_dotpeek_1af59fc93d4d7254f767183701f00e4966>` **(**  **)**                       |
+-------------+----------------------------------------------------------------------------------------------------------------------------------------------+

Public Methods
---------------

+-------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+
|void         |:ref:`DoBuildReportGenerated<classwellfired_peek_application_unity_editor_dotpeek_1a69ad8fbacf003021521a5dcff05e12a9>` **(** string reportAbsolutePath **)**   |
+-------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+

Breakdown
----------

.. _classwellfired_peek_application_unity_editor_dotpeek_1a6019ed665b7d0f4fa95065eaed9fc2dd:

- :ref:`IDotPeekListener<interfacewellfired_peek_application_unity_editor_idotpeeklistener>` **Listener** **{** get; set; **}**

    **Description**

        Give access to .:ref:`Peek<namespacewellfired_peek>` callbacks, like when the report is generated and where it is stored for example. 

.. _classwellfired_peek_application_unity_editor_dotpeek_1a381e1d91dc2dff79988fbc20fa60f8bc:

- :ref:`IVCS<interfacewellfired_peek_application_vcs_ivcs>` **CustomVCS** **{** get; set; **}**

    **Description**

        Allows to provide a custom commit id to .:ref:`Peek<namespacewellfired_peek>` when it is generating the build report. 

.. _classwellfired_peek_application_unity_editor_dotpeek_1a6a07d42db1939a49cee805130f110e30:

- :ref:`Storage<classwellfired_peek_viewmodel_datastorage_storage>` **Storage** **{** get; set; **}**

    **Description**

        Allows to read or modify .:ref:`Peek<namespacewellfired_peek>` settings on the disk. 

.. _classwellfired_peek_application_unity_editor_dotpeek_1abe564db373361aee6b238e2ad0656b3f:

- bool **SessionStarted** 

    **Description**

        Returns true if a session was started already. 

.. _classwellfired_peek_application_unity_editor_dotpeek_1aff402afdbd83366fbb04d443196f51c9:

- :ref:`IDotPeekSession<interfacewellfired_peek_application_idotpeeksession>` **CurrentSession** 

    **Description**

        Returns the current :ref:`IDotPeekSession<interfacewellfired_peek_application_idotpeeksession>`. 

.. _classwellfired_peek_application_unity_editor_dotpeek_1a379f2a1a6f056f71713c8db132af2d1d:

- void **StartSession** **(** BuildTarget target **)**

    **Description**

        Creates a new :ref:`IDotPeekSession<interfacewellfired_peek_application_idotpeeksession>` that will receive the different callbacks from the game engine when build is being processed. When a new session is started, then the previous one is not referenced anymore. 

.. _classwellfired_peek_application_unity_editor_dotpeek_1ad76db20c5995cfda9224e4413113ce84:

- void **EndSession** **(**  **)**

    **Description**

        Finishes a :ref:`IDotPeekSession<interfacewellfired_peek_application_idotpeeksession>`. 

.. _classwellfired_peek_application_unity_editor_dotpeek_1af59fc93d4d7254f767183701f00e4966:

- void **OpenWindow** **(**  **)**

    **Description**

        Open the :ref:`DotPeek<classwellfired_peek_application_unity_editor_dotpeek>` window in :ref:`Unity<namespacewellfired_peek_application_unity>`. 

.. _classwellfired_peek_application_unity_editor_dotpeek_1a69ad8fbacf003021521a5dcff05e12a9:

- void **DoBuildReportGenerated** **(** string reportAbsolutePath **)**

    **Description**

        This is called after the build report was generated and saved on the disk. 

