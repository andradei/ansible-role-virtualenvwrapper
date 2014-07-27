ansible-role-virtualenvwrapper
========

An [Ansible](http://www.ansible.com/home) Role that installs and configures
[virtualenvwrapper](http://virtualenvwrapper.readthedocs.org).

Requirements
------------

The following tools are required:
- [pip](https://pip.pypa.io/en/latest/installing.html) a tool for installing and managing Python packages.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

    `virtualenvwrapper_version` per default set to `4.3.1`

The version of virtualenvwrapper that will be installed.

Dependencies
------------

None.

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - role: "nfb-galaxy.virtualenvwrapper"
           sudo: yes
           tags:
            - virtualenvwrapper
License
-------

MIT

## Author Information

This role was created in 2014 by Gerardo Cepeda Porras.