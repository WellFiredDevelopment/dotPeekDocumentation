.. _enumenumwellfired_peek_application_vcs:

RepositoryStatus
=================

**Namespace:** :ref:`WellFired.Peek.Application.VCS<namespacewellfired_peek_application_vcs>`

Description
------------

Status of the repository 

+---------------+------------------------------------------------------------------------------------------------+
|NotSync        |The repository contains modifications not pushed to the remote repository.                      |
+---------------+------------------------------------------------------------------------------------------------+
|SyncToCommit   |The checked out version is not the latest one, but files does not contains any modification.    |
+---------------+------------------------------------------------------------------------------------------------+
|SyncToHead     |The checked out version is the latest one, and files does not contains any modification.        |
+---------------+------------------------------------------------------------------------------------------------+

