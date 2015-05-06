hostname
========

[![Ansible Galaxy](https://img.shields.io/badge/galaxy-kbrebanov.hostname-660198.svg)](https://galaxy.ansible.com/list#/roles/3391)

Configures hostname

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name          | Default   | Description |
|---------------|-----------|-------------|
| hostname_name | localhost | Hostname    |

Dependencies
------------

None

Example Playbook
----------------

Configure hostname
```
- hosts: all
  roles:
    - { role: hostname, hostname_name: 'example1' }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
