ansible-collectd
================

[![Build Status](https://travis-ci.org/gujo/ansible-collectd.png?branch=master)](https://travis-ci.org/gujo/ansible-collectd)


Install collectd and configure plugins

Requirements
------------

For modern versions of collectd (ie to get the write_graphite plugin) a yum repository with collectd 5 or later is needed. This role provides a repository allthough if used in production you should consider hosting your own mirror.

For ubuntu 12.04 you can install from source to support write_graphite
Role Variables
--------------

collectd_graphite_hostname

collectd_graphite_port

collectd_graphite_host_environment


collectd_mysql_database

collectd_mysql_user

collectd_mysql_password

collectd_has_masterslave - set this to true to enable slave/master logging

collectd_dbmaster - Define this variable on master hosts (if you have any)

TODO
----

Add more plugins

Author
------

Orignal : Johan Gunnarsson <jgunnarsson@gmail.com>
Adham Helal
