========
Security
========

.. _OpenStack Security Guide: http://docs.openstack.org/security-guide/

This document is an attempt to write up all the security measures that
can, will or should be implemented. The basis is the `OpenStack
Security Guide`_ on openstack.org. We use the sections in the security
guide, and try to answer the following questions:

#. Is this security measure implemented? and if not:
#. What are the potential security impact?
#. Other concerns?
#. Should this be implemented?

For each recommendation, there is at least one check that can have one
of four different values:

* ``[PASS]`` This check has been passed
* ``[FAIL]`` This check is failed
* ``[----]`` This check has not been considered yet
* ``[N/A]`` This check is not applicable
* ``[DEFERRED]`` This check has been postponed, will be considered at
  a later time

.. toctree::
    :maxdepth: 2

    documentation
    management
    secure-communication
    api-endpoints
    identity
    dashboard
    compute
    block-storage
    shared-file-systems
    networking
    object-storage
    messaging
    data-processing
    databases
    tenant-data
    instance-management
