Role Name
=========

`pip install`s buildbot bundle and more:

- Google Chrome and
- latest chromedriver

TODO create systemd files for Buildbot

TODO print buildbot user's ~/.ssh/id_rsa.pub to be configured Bitbucket etc.

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
