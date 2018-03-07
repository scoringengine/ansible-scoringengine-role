Role Name
=========

An Ansible role that installs scoring_engine on Ubuntu 16.04

Requirements
------------

Ansible on the deploying system
Python on the remote system

Role Variables
--------------

Available variables are listed below, along with default values:

    mysql_user: engineuser
    mysql_pass: enginepass

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ansible-scoringengine-role, mysql_user: scoring_engine, mysql_pass: scoring_pass }

License
-------

BSD
