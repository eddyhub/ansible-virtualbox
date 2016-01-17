virtualbox
==========

Installs VirtualBox from Oracle's repository

Requirements
------------

This role requires Ansible 2.0 or higher.

Role Variables
--------------

| Name               | Default | Description                      |
|--------------------|---------|----------------------------------|
| virtualbox_version | 5.0     | Version of VirtualBox to install |

Dependencies
------------

Example Playbook
----------------

Install VirtualBox
```
- hosts: all
  roles:
    - { role: eddyhub.virtualbox }
```

Install a specific version of VirtualBox
```
- hosts: all
  roles:
    - { role: eddyhub.virtualbox, virtualbox_version: 5.0 }
```

License
-------

BSD

Author Information
------------------

Eduard Angold

