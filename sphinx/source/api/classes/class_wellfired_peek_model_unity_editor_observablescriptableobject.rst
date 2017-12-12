.. _classwellfired_peek_model_unity_editor_observablescriptableobject:

ObservableScriptableObject
===========================

**Namespace:** :ref:`WellFired.Peek.Model.Unity<namespacewellfired_peek_model_unity>`

Description
------------



Events
-------

+------------------------------+--------------------------------------------------------------------------------------------------------------------------------+
|PropertyChangedEventHandler   |:ref:`PropertyChanged<classwellfired_peek_model_unity_editor_observablescriptableobject_1a96feaf54d0b866abc146a87272165403>`    |
+------------------------------+--------------------------------------------------------------------------------------------------------------------------------+

protected-func
---------------

+-------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|bool         |:ref:`SetProperty< T ><classwellfired_peek_model_unity_editor_observablescriptableobject_1acbc74138cbb59039ff52cce07a6caaa4>` **(** ref T storage, T value, string propertyName = @"" **)**   |
+-------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Breakdown
----------

.. _classwellfired_peek_model_unity_editor_observablescriptableobject_1a96feaf54d0b866abc146a87272165403:

- PropertyChangedEventHandler **PropertyChanged** 

.. _classwellfired_peek_model_unity_editor_observablescriptableobject_1acbc74138cbb59039ff52cce07a6caaa4:

- bool **SetProperty< T >** **(** ref T storage, T value, string propertyName = @"" **)**

    **Description**

        Sets the property if the objects are different (This is in order to prevent recursion with two way binding). This will return a boolean that states the outcome of the operation. 

