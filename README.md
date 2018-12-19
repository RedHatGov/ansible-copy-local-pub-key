copy-local-pub-key
=========

Copys the local SSH public key to authorized_keys file of target

Requirements
------------

An existing SSH identity on localhost

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: servers
  gather_facts: no
  roles:
    - redhatgov.copy-local-pub-key
```

License
-------

GPLv3

Author Information
------------------

[Red Hat North American Public Sector Solution Architects](https://redhatgov.io)
