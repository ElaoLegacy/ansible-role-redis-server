Ansible Role - Redis Server
===========================

A redis server role to install redis server on elao symfony standard vagrant box

Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.redis-server }

License
-------

MIT

Author Information
------------------

http://www.elao.com/
