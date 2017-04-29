Debian-Ømq
==========

Distributed Computing Made Simple.

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-zeromq }

Tasks
-----

  - Install [ØMQ](http://zeromq.org/) library

License
-------

BSD
