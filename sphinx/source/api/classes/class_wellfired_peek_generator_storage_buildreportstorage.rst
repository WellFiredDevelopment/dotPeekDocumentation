.. _classwellfired_peek_generator_storage_buildreportstorage:

BuildReportStorage
===================

**Namespace:** :ref:`WellFired.Peek.Generator<namespacewellfired_peek_generator>`

**Implements:** :ref:`WellFired.Peek.Generator.Storage.IBuildReportStorage<interfacewellfired_peek_generator_storage_ibuildreportstorage>`


Description
------------



Public Methods
---------------

+--------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|                                                                          |:ref:`BuildReportStorage<classwellfired_peek_generator_storage_buildreportstorage_1a7969096832b3e3e9c2e45ad75f12c785>` **(** :ref:`IBuildReportSerializer<interfacewellfired_peek_generator_storage_ibuildreportserializer>` serializer, :ref:`IFileStorage<interfacewellfired_peek_generator_storage_ifilestorage>` fileStorage **)**   |
+--------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|async Task< bool >                                                        |:ref:`Save<classwellfired_peek_generator_storage_buildreportstorage_1a4f7521bcc0ad54f6d6e51dc75f0fac6f>` **(** :ref:`BuildReport<classwellfired_peek_model_buildreport>` buildReport, string path **)**                                                                                                                                  |
+--------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|async Task< :ref:`BuildReport<classwellfired_peek_model_buildreport>` >   |:ref:`Load<classwellfired_peek_generator_storage_buildreportstorage_1af0436dc3a11a8fa1845cef21c4ef7626>` **(** string path **)**                                                                                                                                                                                                         |
+--------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Public Static Methods
----------------------

+--------------------------------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
|:ref:`BuildReportStorage<classwellfired_peek_generator_storage_buildreportstorage>`   |:ref:`GetDefaultReportStorage<classwellfired_peek_generator_storage_buildreportstorage_1a31fb1165f182c1f88b4cf5e076694963>` **(**  **)**   |
+--------------------------------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+

Breakdown
----------

.. _classwellfired_peek_generator_storage_buildreportstorage_1a7969096832b3e3e9c2e45ad75f12c785:

-  **BuildReportStorage** **(** :ref:`IBuildReportSerializer<interfacewellfired_peek_generator_storage_ibuildreportserializer>` serializer, :ref:`IFileStorage<interfacewellfired_peek_generator_storage_ifilestorage>` fileStorage **)**

.. _classwellfired_peek_generator_storage_buildreportstorage_1a4f7521bcc0ad54f6d6e51dc75f0fac6f:

- async Task< bool > **Save** **(** :ref:`BuildReport<classwellfired_peek_model_buildreport>` buildReport, string path **)**

.. _classwellfired_peek_generator_storage_buildreportstorage_1af0436dc3a11a8fa1845cef21c4ef7626:

- async Task< :ref:`BuildReport<classwellfired_peek_model_buildreport>` > **Load** **(** string path **)**

.. _classwellfired_peek_generator_storage_buildreportstorage_1a31fb1165f182c1f88b4cf5e076694963:

- :ref:`BuildReportStorage<classwellfired_peek_generator_storage_buildreportstorage>` **GetDefaultReportStorage** **(**  **)**

