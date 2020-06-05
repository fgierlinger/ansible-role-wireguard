# Ansible role wireguard
=========

Install and configure wireguard

Requirements
------------

None

Role Variables
--------------

* `wireguard_kernel_version` specify which kernel the module should be built against.
    * Default: _Current kernel version_
See (defaults/main.yml)[defaults/main.yml]

Dependencies
------------

None

Example Playbook
----------------

    - hosts: wireguard
      vars:
      roles:
	    - fgierlinger.wireguard

License
-------

CC-BY-SA

Contribution
------------

You want to contribute? Great! See [TODO.md](TODO.md) for an idea of tasks that
need to be done. Feel free to send a pull request when you are done with your
development.

Author Information
------------------

Frédéric Gierlinger
