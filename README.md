stack-common
=========

This role is used by ENA for items that are "common" across all ENA stacks.  For example, we want to ensure that curl is
installed on all stacks, so we added a task that ensures that it will be installed.

Requirements
------------

There are currently no external requirements for this role.

Role Variables
--------------

There are currently no variables for this role.

Dependencies
------------

There are currently no external role dependencies for this role.

Example Playbook
----------------
```yaml
- hosts: all
  roles:
    - stack-common
```

License
-------

Apache License 2.0

Author Information
------------------

Education Networks of America
