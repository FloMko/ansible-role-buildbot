Role Name
=========

Installs Buildbot

TODO create systemd files for Buildbot

Role Variables
--------------

server_name should be a fully qualified domain name of buildbot host

Example Playbook
----------------

How to use role:

    - hosts: buildbots
      roles:
         - { role: ysz.buildbot, server_name: buildbot.foo.com }

License
-------

BSD
