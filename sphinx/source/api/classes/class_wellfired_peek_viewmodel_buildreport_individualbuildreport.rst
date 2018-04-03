.. _classwellfired_peek_viewmodel_buildreport_individualbuildreport:

IndividualBuildReport
======================

**Namespace:** :ref:`WellFired.Peek.ViewModel<namespacewellfired_peek_viewmodel>`

**Implements:** :ref:`WellFired.Peek.ViewModel.IDetailItem<interfacewellfired_peek_viewmodel_idetailitem>`


Description
------------



Properties
-----------

+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
|IEnumerable< ObservableBase >   |:ref:`TabSource<classwellfired_peek_viewmodel_buildreport_individualbuildreport_1a02062d396b68396fbc3c998ebf83765a>` **{** get; set; **}**      |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
|object                          |:ref:`SelectedPage<classwellfired_peek_viewmodel_buildreport_individualbuildreport_1a9fc94594082b34620adf623fed2ce9e7>` **{** get; set; **}**   |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
|DateTime                        |:ref:`BuildDate<classwellfired_peek_viewmodel_buildreport_individualbuildreport_1a97a91afb6dff4e26a791ff7fbf6349aa>` **{** get; set; **}**      |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
|bool                            |:ref:`IsSelected<classwellfired_peek_viewmodel_buildreport_individualbuildreport_1a0b0f39d66f208da819aaa8545623a275>` **{** get; set; **}**     |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
|string                          |:ref:`FileName<classwellfired_peek_viewmodel_buildreport_individualbuildreport_1ac4e2daa9c29b3da4970c1a2d129efdda>` **{** get; set; **}**       |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+

Public Methods
---------------

+-------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|             |:ref:`IndividualBuildReport<classwellfired_peek_viewmodel_buildreport_individualbuildreport_1a9fe1a61e777cf9275803113efc469357>` **(** :ref:`IBuildReportStorage<interfacewellfired_peek_generator_storage_ibuildreportstorage>` buildReportStorage, string filename **)**   |
+-------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|async Task   |:ref:`LoadReport<classwellfired_peek_viewmodel_buildreport_individualbuildreport_1a27541a82ab0088a74878727d9550cc67>` **(** string reportLocation, Type previousSelectedPage **)**                                                                                           |
+-------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Breakdown
----------

.. _classwellfired_peek_viewmodel_buildreport_individualbuildreport_1a02062d396b68396fbc3c998ebf83765a:

- IEnumerable< ObservableBase > **TabSource** **{** get; set; **}**

.. _classwellfired_peek_viewmodel_buildreport_individualbuildreport_1a9fc94594082b34620adf623fed2ce9e7:

- object **SelectedPage** **{** get; set; **}**

.. _classwellfired_peek_viewmodel_buildreport_individualbuildreport_1a97a91afb6dff4e26a791ff7fbf6349aa:

- DateTime **BuildDate** **{** get; set; **}**

.. _classwellfired_peek_viewmodel_buildreport_individualbuildreport_1a0b0f39d66f208da819aaa8545623a275:

- bool **IsSelected** **{** get; set; **}**

.. _classwellfired_peek_viewmodel_buildreport_individualbuildreport_1ac4e2daa9c29b3da4970c1a2d129efdda:

- string **FileName** **{** get; set; **}**

.. _classwellfired_peek_viewmodel_buildreport_individualbuildreport_1a9fe1a61e777cf9275803113efc469357:

-  **IndividualBuildReport** **(** :ref:`IBuildReportStorage<interfacewellfired_peek_generator_storage_ibuildreportstorage>` buildReportStorage, string filename **)**

.. _classwellfired_peek_viewmodel_buildreport_individualbuildreport_1a27541a82ab0088a74878727d9550cc67:

- async Task **LoadReport** **(** string reportLocation, Type previousSelectedPage **)**

