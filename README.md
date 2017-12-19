sqlmap
=========

Ansible role to install sqlmap injection and database takeover tool.

Requirements
------------

None

Role Variables
--------------

sqlmap_git_location: '/opt'

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: leesoh.sqlmap }

License
-------

BSD

Author Information
------------------

sqlmap: http://sqlmap.org
