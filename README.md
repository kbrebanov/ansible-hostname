[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

hostname
========

[![Build Status](https://travis-ci.org/kbrebanov/ansible-hostname.svg?branch=master)](https://travis-ci.org/kbrebanov/ansible-hostname)

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
