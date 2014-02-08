ansible-collectd
================

Install collectd and configure plugins

Requirements
------------

For modern versions of collectd (ie to get the write_graphite plugin) a yum repository with collectd 5 or later is needed. This role provides a repository allthough if used in production you should consider hosting your own mirror.


Role Variables
--------------

collectd_graphite_hostname

collectd_graphite_port

collectd_graphite_host_environment


collectd_mysql_database

collectd_mysql_user

collectd_mysql_password

TODO
----

Add more plugins

Author
------

Johan Gunnarsson <jgunnarsson@gmail.com>
