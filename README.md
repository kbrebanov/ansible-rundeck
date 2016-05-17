rundeck
=======

[![Build Status](https://travis-ci.org/kbrebanov/ansible-rundeck.svg?branch=master)](https://travis-ci.org/kbrebanov/ansible-rundeck)

Installs Rundeck

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

| Name            | Default | Description                   |
|:----------------|:--------|:------------------------------|
| rundeck_version | 2.6.7   | Version of Rundeck to install |

Dependencies
------------

- kbrebanov.java (Java 7)

Example Playbook
----------------

Install Rundeck
```yaml
- hosts: all
  roles:
    - kbrebanov.rundeck
```

Install Rundeck specifying version
```yaml
- hosts: all
  vars:
    rundeck_version: 2.4.1
  roles:
    - kbrebanov.rundeck
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
