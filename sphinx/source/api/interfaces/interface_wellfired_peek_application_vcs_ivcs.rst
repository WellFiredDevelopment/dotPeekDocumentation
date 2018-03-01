.. _interfacewellfired_peek_application_vcs_ivcs:

IVCS
=====

**Namespace:** :ref:`WellFired.Peek.Application<namespacewellfired_peek_application>`

Description
------------

Classes implementing this interface can provide the current commit id. This can be useful when you are using a :ref:`VCS<namespacewellfired_peek_application_vcs>` not supported by .:ref:`Peek<namespacewellfired_peek>` or running your build on a CI where .:ref:`Peek<namespacewellfired_peek>` does not have access to your :ref:`VCS<namespacewellfired_peek_application_vcs>` system. 

Public Methods
---------------

+-------------+-------------------------------------------------------------------------------------------------------------------+
|string       |:ref:`GetCommitId<interfacewellfired_peek_application_vcs_ivcs_1a19131e5d85647b6ffca02404020570ef>` **(**  **)**   |
+-------------+-------------------------------------------------------------------------------------------------------------------+

Breakdown
----------

.. _interfacewellfired_peek_application_vcs_ivcs_1a19131e5d85647b6ffca02404020570ef:

- string **GetCommitId** **(**  **)**

    **Description**

        Provide the current commit id. 

