ansible-powerdns
================

Role to deploy powerdns, powerdns will be deployed in docker container, 
variables are located in a local folder.

Requirements
------------

None

Role Variables
--------------

Variables could be found in the defaults/main path

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: dns
    roles:
        - { role: dorancemc.ansible-powerdns }
```

License
-------

Apache-2.0

Author Information
------------------

Dorance Martinez @dorancemc
