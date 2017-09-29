Ansible-Role: Webscan
=========

Adjusts configuration of a system that is subject to web security and vulnerability scanning . Designed to be safe to run mid-scan.

Requirements
------------

none

Role Variables
--------------

TBD

Dependencies
------------

Currently assumes the system in question in running apache.
Tacitly further assumes that apache was installed and configured by or in a way
similar to our [apache role](https://github.com/dheles/ansible-role-apache).

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: webscan }

License
-------

CC0

Author Information
------------------

Drew Heles
