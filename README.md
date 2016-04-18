Ansible Role: zerorpc Python
=========

Install zerorpc Python on CentOS server.

Requirements
------------

Written in Ansible 1.9.*

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

### zerorpc_version

Install zerorpc package, default version is `0.5.1`.

Dependencies
------------

juwai.python27

Example Playbook
----------------

    - hosts: servers
      roles:
        - juwai.zerorpc-python

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2016 by [Juwai Limited](http://www.juwai.com).
