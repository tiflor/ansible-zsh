Role Name
=========

A simple Ansible role to install and configure zsh.
Configuration file [.zshrc](https://raw.githubusercontent.com/grml/grml-etc-core/master/etc/zsh/zshrc) is based on the [grml project](http://grml.org/).
 
Requirements
------------

none

Role Variables
--------------

none

Dependencies
------------

none

Example Playbook
----------------

    - hosts: localhost
      roles:
         - { role: tiflor.ansible_zsh }

License
-------

MIT

Author Information
------------------

[tiflor@github](https://github.com/tiflor)
