mysql
=========

[![Build Status](https://travis-ci.org/sirReeall/mysql.svg?branch=master)](https://travis-ci.org/sirReeall/mysql)

Ansible role for installing mysql.

Currently this will only install mysql 5.7 using yum.

MySQL Password Validate Plugin is installed by default. This is done using my.cnf file.

The validate_password_policy is set to LOW. This is also done using my.cnf file.

Requirements
------------

None

Role Variables
--------------

| Name | Default | Remarks |
| --- | --- | --- |
| mysql_root_password | alfresco.123 | Password for root@localhost account |

Dependencies
------------

Node

Example Playbook
----------------

- hosts: servers
  roles:
      - { role: sirreeall.mysql }

License
-------

Free
