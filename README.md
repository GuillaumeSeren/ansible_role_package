ansible_role_pakage
=========

Ansible role to manage packages and packages manager

Requirements
------------

This role need docker

Role Variables
--------------
* pkg_sync_period: Update if this time is elapsed
* pkg_sync_period_mirror: Update if this time is elapsed

Features
--------
* Configure package manager
* Check if update is need according to pkg_sync_period

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

GPLv3

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
