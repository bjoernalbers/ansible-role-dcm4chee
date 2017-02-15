Ansible Role: DCM4CHEE
======================

Install DCM4CHEE Archive v5 on Ubuntu Linux.

Requirements
------------

PostgreSQL should be running.
You have to provide creditials for the PostgreSQL admin role.

Role Variables
--------------

RTFS (Read The Fine Source code)!

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

This Ansible role is released under the [MIT License](LICENSE.txt).
