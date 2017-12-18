Ansible Role - OpenSSL Heartbleed Upgrade
=========
[![Travis Status](https://img.shields.io/travis/Artemu/ansible-core-heartbleed.svg?style=flat-square)](https://travis-ci.org/Artemu/ansible-core-heartbleed) [![Ansible Downloads](https://img.shields.io/ansible/role/d/22874.svg?style=flat-square)](https://galaxy.ansible.com/Artemu/core-heartbleed/)
[![Ansible Role](https://img.shields.io/ansible/role/22874.svg?style=flat-square)](https://galaxy.ansible.com/Artemu/core-heartbleed/)

The following role is used to push updates, and ensure that the OpenSSL version has been updated and is working.

Requirements
------------
This role has no requirements.

Role Variables
--------------
This role takes no input variables.

Dependencies
------------

This role has no dependencies.

Example Playbook
----------------
```yaml
---
  - hosts: all
    become: true

    roles:
      - Artemu.core-heartbleed
```

License
-------

To be updated

Author Information
------------------

This role has been written by Kyle Lindeque
