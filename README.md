rundeck
=======

Installs Rundeck

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name            | Default | Description                   |
|-----------------|---------|-------------------------------|
| rundeck_version | 2.4.2   | Version of Rundeck to install |

Dependencies
------------

- kbrebanov.java (Java 7)

Example Playbook
----------------

Install Rundeck
```
- hosts: all
  roles:
    - { role: kbrebanov.rundeck }
```

Install Rundeck specifying version
```
- hosts: all
  roles:
    - { role: kbrebanov.rundeck, rundeck_version: 2.4.1 }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
