elasticsearch
=========

This is a role to install Elasticsearch.

Requirements
------------

 - Ubuntu 22 or previous

Role Variables
--------------




Example Playbook
----------------

Role must run as root user in order to make changes to the system.

```
  - name: Install Elasticsearch
  - hosts: servers
    roles:
         - { role: ricardobarbosa.elasticsearch }
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
