.. _classwellfired_peek_view_views_sourceboundmasterpage:

SourceBoundMasterPage
======================

**Namespace:** :ref:`WellFired.Peek.View<namespacewellfired_peek_view>`

Description
------------



public-static-attrib
---------------------

+----------------------------+--------------------------------------------------------------------------------------------------------------------+
|readonly BindableProperty   |:ref:`SourceProperty<classwellfired_peek_view_views_sourceboundmasterpage_1aa00a27ee8f2ce6ad84c87d7cfa2588ab>`      |
+----------------------------+--------------------------------------------------------------------------------------------------------------------+
|readonly BindableProperty   |:ref:`TemplateProperty<classwellfired_peek_view_views_sourceboundmasterpage_1adec421faba455dc625a51f7378539830>`    |
+----------------------------+--------------------------------------------------------------------------------------------------------------------+

Properties
-----------

+-------------------------+---------------------------------------------------------------------------------------------------------------------------------+
|INotifyPropertyChanged   |:ref:`Source<classwellfired_peek_view_views_sourceboundmasterpage_1a1d8d7148544093a5187853cbb446318a>` **{** get; set; **}**     |
+-------------------------+---------------------------------------------------------------------------------------------------------------------------------+
|DataTemplate             |:ref:`Template<classwellfired_peek_view_views_sourceboundmasterpage_1a3a4e45e841f79dc612a33b9e23490ca3>` **{** get; set; **}**   |
+-------------------------+---------------------------------------------------------------------------------------------------------------------------------+

protected-func
---------------

+----------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|                |:ref:`SourceBoundMasterPage<classwellfired_peek_view_views_sourceboundmasterpage_1ac7e2c5cf213d430529b9ffa84b751233>` **(** ILayoutable master, IView detail **)**        |
+----------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|override void   |:ref:`OnPropertyChanged<classwellfired_peek_view_views_sourceboundmasterpage_1a71d5da6815a2556ef8559ff3134818da>` **(** object sender, PropertyChangedEventArgs e **)**   |
+----------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Breakdown
----------

.. _classwellfired_peek_view_views_sourceboundmasterpage_1aa00a27ee8f2ce6ad84c87d7cfa2588ab:

- readonly BindableProperty **SourceProperty** 

    **Description**

        When providing a backing store, the Source can be bound to to define what should be displayed in the Detail Page. This is used in conjunction with the Template to define what should be displayed in the Detail :ref:`View<namespacewellfired_peek_view>`. 

.. _classwellfired_peek_view_views_sourceboundmasterpage_1adec421faba455dc625a51f7378539830:

- readonly BindableProperty **TemplateProperty** 

    **Description**

        The templace is responsible for deciding what the view should render when the Source has changed. 

.. _classwellfired_peek_view_views_sourceboundmasterpage_1a1d8d7148544093a5187853cbb446318a:

- INotifyPropertyChanged **Source** **{** get; set; **}**

    **Description**

        When providing a backing store, the Source can be bound to to define what should be displayed in the Detail Page. This is used in conjunction with the Template to define what should be displayed in the Detail :ref:`View<namespacewellfired_peek_view>`. 

.. _classwellfired_peek_view_views_sourceboundmasterpage_1a3a4e45e841f79dc612a33b9e23490ca3:

- DataTemplate **Template** **{** get; set; **}**

    **Description**

        The templace is responsible for deciding what the view should render when the Source has changed. 

.. _classwellfired_peek_view_views_sourceboundmasterpage_1ac7e2c5cf213d430529b9ffa84b751233:

-  **SourceBoundMasterPage** **(** ILayoutable master, IView detail **)**

.. _classwellfired_peek_view_views_sourceboundmasterpage_1a71d5da6815a2556ef8559ff3134818da:

- override void **OnPropertyChanged** **(** object sender, PropertyChangedEventArgs e **)**

