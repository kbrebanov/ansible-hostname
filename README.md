hostname
========

[![Ansible Role](https://img.shields.io/ansible/role/3391.svg)](https://galaxy.ansible.com/list#/roles/3391)

Configures hostname

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

| Name          | Default                | Description |
|:--------------|:-----------------------|:------------|
| hostname_name | {{ ansible_hostname }} | Hostname    |

Dependencies
------------

None

Example Playbook
----------------

Configure hostname
```yaml
- hosts: all
  vars:
    hostname_name: example1
  roles:
    - role: kbrebanov.hostname
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
