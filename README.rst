Role-Pandoc
===========

This ansible role installs pandoc on Debian systems.

Requirements
------------

If pandoc is already installed, this role will not modify the target system.

Role Variables
--------------

================= =========================================== ==============
Variable          Purpose                                     Default value
----------------- ------------------------------------------- --------------
pandoc_version    The target version of pandoc to install     1.17.2
================= =========================================== ==============

Example Playbook
----------------

Including an example of how to use your role (for instance, with
variables passed in as parameters) is always nice for users too:

::

    - hosts: servers
      roles:
         - { role: role-pandoc, pandoc_version: 1.10.0 }

License
-------

BSD
