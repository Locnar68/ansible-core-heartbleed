Ansible Role - OpenSSL Heartbleed Upgrade
=========
[![Travis Status](https://img.shields.io/travis/artemu/ansible-core-heartbleed.svg?style=flat-square)](https://travis-ci.org/Artemu/ansible-core-heartbleed)

The following role is for the use of ensuring the servers are not vulnerable to the Heartbleed attack.

Requirements
------------

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: artemu.core.heartbleed }

License
-------

BSD

Author Information
------------------

--
