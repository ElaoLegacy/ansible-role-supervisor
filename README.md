WARNING: This role is no longer maintained !!!
==============================================

You are strongly encouraged to switch to the new roles stack on https://github.com/ElaoInfra
--------------------------------------------------------------------------------------------

By the way, this role will remain available on https://github.com/ElaoLegacy
----------------------------------------------------------------------------


Ansible Role - Supervisor
=========================

A supervisor role for elao symfony standard vagrant box

Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian


Role Handlers
-------------

    supervisor restart  # Restart supervisor service


Role Variables
--------------

    elao_supervisor_httpd: '{{ elao_env == "dev" }}'  # Enable http server (true|false)


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
