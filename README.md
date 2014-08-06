Ansible Role - Supervisor
=========================

A supervisor role for elao symfony standard vagrant box

Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian

Role Handlers
-------------

* supervisor restart: Restart supervisor service

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.supervisor }

License
-------

MIT

Author Information
------------------

http://www.elao.com/
