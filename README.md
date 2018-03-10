ansible-scoringengine-role [![Build Status](https://travis-ci.org/RustyBower/ansible-scoringengine-role.svg?branch=master)](https://travis-ci.org/RustyBower/ansible-scoringengine-role)
=========

An Ansible role that installs scoring_engine on Ubuntu 16.04 and Debian 9

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
