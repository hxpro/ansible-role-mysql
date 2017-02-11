hxpro.mysql
===========

Install MySQL Server 5.7 Community Edition on CentOS 7

Requirements
------------

TODO

Role Variables
--------------

mysql_datadir: /var/lib/mysql

Dependencies
------------

- hxpro.epel

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: hxpro.mysql }

License
-------

WTFPL

Author Information
------------------

Matěj Koudelka <matej@hxpro.cz>
