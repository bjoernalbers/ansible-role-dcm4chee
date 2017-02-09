Ansible Role: DCM4CHEE
======================

[![Build Status](https://travis-ci.org/bjoernalbers/ansible-role-dcm4chee.svg?branch=master)](https://travis-ci.org/bjoernalbers/ansible-role-dcm4chee)

Install DCM4CHEE Archive v5 on Ubuntu Linux.

Requirements
------------

PostgreSQL should be running.
You have to provide creditials for the PostgreSQL admin role.

Role Variables
--------------

RTFS (Read The Fine Source coode)!

Dependencies
------------

- bjoernalbers.wildfly

Example Playbook
----------------

```yaml
- hosts: pacs
  roles:
     - { role: bjoernalbers.dcm4chee }
```

License
-------

This Ansible role is released unter the [MIT License](LICENSE.txt).
