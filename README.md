hxpro.mysql
===========

Install MySQL Server 5.7 Community Edition on CentOS 7

TODO
----
http://crashmag.net/change-the-default-mysql-data-directory-with-selinux-enabled

Requirements
------------

TODO

Role Variables
--------------
 - mysql_vars:
     datadir: /var/lib/mysql
     max_allowed_packet: 16M
     server_id: 1

This variables are deprecated! Please use mysql_vars instead
 - mysql_datadir: /var/lib/mysql
 - mysql_max_allowed_packet: 16M
 - mysql_server_id: 1

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
