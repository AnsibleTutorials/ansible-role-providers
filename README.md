Providers
=========

Gets different providers on common ground for other roles

Supported Providers
-------------------

- Vagrant
- DigitalOcean

Requirements
------------

None

Role Variables
--------------

- **user_username**: ansible
- **user_password**: <HASH> (ansible)

Dependencies
------------

None

Example Playbook
----------------

    - hosts: all
      roles:
         - ryanlelek.providers

License
-------

MIT

Author Information
------------------

Created by [Ryan Lelek](https://www.ryanlelek.com)  
Part of [AnsibleTutorials.com](http://www.ansibletutorials.com)
