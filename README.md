Ansible-Role: BanTheMan
=========

Adjusts configuration of a system to block access to given paths from given IPs. Kind of a manual fail2ban. Primary use case is on-the-fly reconfiguration of a system that is subject to a web security and vulnerability scanning or a problematic level of webcrawling. Designed to be safe to run mid-scan or -crawl.

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
         - { role: bantheman }

License
-------

CC0

Author Information
------------------

Drew Heles
