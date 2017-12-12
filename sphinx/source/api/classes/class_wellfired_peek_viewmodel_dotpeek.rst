.. _classwellfired_peek_viewmodel_dotpeek:

DotPeek
========

**Namespace:** :ref:`WellFired.Peek<namespacewellfired_peek>`

**Implements:** :ref:`WellFired.Peek.ViewModel.IBuildReportsListerClient<interfacewellfired_peek_viewmodel_ibuildreportslisterclient>`


Description
------------



Properties
-----------

+----------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------+
|ObservableCollection< :ref:`IndividualBuildGroup<classwellfired_peek_viewmodel_individualbuildgroup>` >   |:ref:`GroupedBuildReports<classwellfired_peek_viewmodel_dotpeek_1a883a29be7bdae1c092fcd84c22c92580>` **{** get; set; **}**   |
+----------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------+
|:ref:`IndividualBuildGroup<classwellfired_peek_viewmodel_individualbuildgroup>`                           |:ref:`PinnedBuildReports<classwellfired_peek_viewmodel_dotpeek_1af6a1e8a10a79d1fb8422463dd8c92ff6>` **{** get; set; **}**    |
+----------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------+
|:ref:`IndividualBuildGroup<classwellfired_peek_viewmodel_individualbuildgroup>`                           |:ref:`AllBuildReports<classwellfired_peek_viewmodel_dotpeek_1ad490374678d308ff83a963ddfb3f7ec4>` **{** get; set; **}**       |
+----------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------+
|string                                                                                                    |:ref:`BuildReportPath<classwellfired_peek_viewmodel_dotpeek_1a70faf7f480eb8958662afc1a420c47c9>` **{** get; set; **}**       |
+----------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------+
|:ref:`IndividualBuildReport<classwellfired_peek_viewmodel_buildreport_individualbuildreport>`             |:ref:`SelectedItem<classwellfired_peek_viewmodel_dotpeek_1a79f256f05baa3480f795747af5fc696e>` **{** get; set; **}**          |
+----------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------+
|ObservableBase                                                                                            |:ref:`DetailSource<classwellfired_peek_viewmodel_dotpeek_1a306ca103465b70b07302f28ec9b82a64>` **{** get; set; **}**          |
+----------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------+
|Command                                                                                                   |:ref:`OpenSettingsCommand<classwellfired_peek_viewmodel_dotpeek_1afe3a514f643e6bfaa63735d190c6f0ef>` **{** get; set; **}**   |
+----------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------+
|:ref:`Settings<classwellfired_peek_viewmodel_settings>`                                                   |:ref:`Settings<classwellfired_peek_viewmodel_dotpeek_1a62cc0b914371c2dd22c2acbccb6bda8e>` **{** get; set; **}**              |
+----------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------+

Public Methods
---------------

+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|void         |:ref:`Inject<classwellfired_peek_viewmodel_dotpeek_1a73d0b71e88113cbc5258069dd04c6a63>` **(** ILogger logger, INotifyPropertyChanged persistentData, IPlatformProvider platformProvider **)**   |
+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Breakdown
----------

.. _classwellfired_peek_viewmodel_dotpeek_1a883a29be7bdae1c092fcd84c22c92580:

- ObservableCollection< :ref:`IndividualBuildGroup<classwellfired_peek_viewmodel_individualbuildgroup>` > **GroupedBuildReports** **{** get; set; **}**

.. _classwellfired_peek_viewmodel_dotpeek_1af6a1e8a10a79d1fb8422463dd8c92ff6:

- :ref:`IndividualBuildGroup<classwellfired_peek_viewmodel_individualbuildgroup>` **PinnedBuildReports** **{** get; set; **}**

    **Description**

        This is an easy accessor into our pinned data. 

.. _classwellfired_peek_viewmodel_dotpeek_1ad490374678d308ff83a963ddfb3f7ec4:

- :ref:`IndividualBuildGroup<classwellfired_peek_viewmodel_individualbuildgroup>` **AllBuildReports** **{** get; set; **}**

    **Description**

        This is an easy accessor into all of our build reports 

.. _classwellfired_peek_viewmodel_dotpeek_1a70faf7f480eb8958662afc1a420c47c9:

- string **BuildReportPath** **{** get; set; **}**

.. _classwellfired_peek_viewmodel_dotpeek_1a79f256f05baa3480f795747af5fc696e:

- :ref:`IndividualBuildReport<classwellfired_peek_viewmodel_buildreport_individualbuildreport>` **SelectedItem** **{** get; set; **}**

.. _classwellfired_peek_viewmodel_dotpeek_1a306ca103465b70b07302f28ec9b82a64:

- ObservableBase **DetailSource** **{** get; set; **}**

.. _classwellfired_peek_viewmodel_dotpeek_1afe3a514f643e6bfaa63735d190c6f0ef:

- Command **OpenSettingsCommand** **{** get; set; **}**

.. _classwellfired_peek_viewmodel_dotpeek_1a62cc0b914371c2dd22c2acbccb6bda8e:

- :ref:`Settings<classwellfired_peek_viewmodel_settings>` **Settings** **{** get; set; **}**

.. _classwellfired_peek_viewmodel_dotpeek_1a73d0b71e88113cbc5258069dd04c6a63:

- void **Inject** **(** ILogger logger, INotifyPropertyChanged persistentData, IPlatformProvider platformProvider **)**

