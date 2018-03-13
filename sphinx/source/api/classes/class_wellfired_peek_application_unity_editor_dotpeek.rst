.. _classwellfired_peek_application_unity_editor_dotpeek:

DotPeek
========

**Namespace:** :ref:`WellFired.Peek.Application.Unity<namespacewellfired_peek_application_unity>`

**Implements:** :ref:`WellFired.Peek.Application.IDotPeekApplicationListener<interfacewellfired_peek_application_idotpeekapplicationlistener>`


Description
------------

This is a public wrapper around .:ref:`Peek<namespacewellfired_peek>` application. It gives access to different utilities allowing a total control of .:ref:`Peek<namespacewellfired_peek>`. 

Properties
-----------

+---------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------+
|:ref:`IDotPeekListener<interfacewellfired_peek_application_unity_editor_idotpeeklistener>`   |:ref:`Listener<classwellfired_peek_application_unity_editor_dotpeek_1a6019ed665b7d0f4fa95065eaed9fc2dd>` **{** get; set; **}**         |
+---------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------+
|:ref:`IVCS<interfacewellfired_peek_application_vcs_ivcs>`                                    |:ref:`CustomVCS<classwellfired_peek_application_unity_editor_dotpeek_1a381e1d91dc2dff79988fbc20fa60f8bc>` **{** get; set; **}**        |
+---------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------+
|:ref:`Storage<classwellfired_peek_viewmodel_datastorage_storage>`                            |:ref:`Storage<classwellfired_peek_application_unity_editor_dotpeek_1a6a07d42db1939a49cee805130f110e30>` **{** get; set; **}**          |
+---------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------+
|:ref:`IDotPeekApplication<interfacewellfired_peek_application_idotpeekapplication>`          |:ref:`NewApplication<classwellfired_peek_application_unity_editor_dotpeek_1a060d3530544a95556c42d4f9c5d0ccef>` **{** get; set; **}**   |
+---------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------+

public-static-attrib
---------------------

+--------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------+
|:ref:`IDotPeekApplication<interfacewellfired_peek_application_idotpeekapplication>`   |:ref:`CurrentApplication<classwellfired_peek_application_unity_editor_dotpeek_1aea375075bf499b7c4410e64f52bfecbc>`    |
+--------------------------------------------------------------------------------------+----------------------------------------------------------------------------------------------------------------------+

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

.. _classwellfired_peek_application_unity_editor_dotpeek_1a060d3530544a95556c42d4f9c5d0ccef:

- :ref:`IDotPeekApplication<interfacewellfired_peek_application_idotpeekapplication>` **NewApplication** **{** get; set; **}**

    **Description**

        Create a new :ref:`IDotPeekApplication<interfacewellfired_peek_application_idotpeekapplication>` that will receive the different callbacks from the game engine when build is being processed. When a new session is required, then the previous one is garbage collected. 

.. _classwellfired_peek_application_unity_editor_dotpeek_1aea375075bf499b7c4410e64f52bfecbc:

- :ref:`IDotPeekApplication<interfacewellfired_peek_application_idotpeekapplication>` **CurrentApplication** 

    **Description**

        Returns the current :ref:`IDotPeekApplication<interfacewellfired_peek_application_idotpeekapplication>`. 

.. _classwellfired_peek_application_unity_editor_dotpeek_1a69ad8fbacf003021521a5dcff05e12a9:

- void **DoBuildReportGenerated** **(** string reportAbsolutePath **)**

    **Description**

        This is called after the build report was generated and saved on the disk. 

    **Parameters**

        +---------------------+--------------------------------+
        |reportAbsolutePath   |Location of the build report.   |
        +---------------------+--------------------------------+
        
