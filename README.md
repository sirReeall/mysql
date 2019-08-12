mysql
=========

Ansible role for installing mysql.

Currently this will only install mysql 5.7 using yum.

This also adjust the password policy to LOW.

Requirements
------------

None

Role Variables
--------------

Everything is currently hardcodes and no variables are exposed

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
