Ansible Yubikey SSH
=========

[![Galaxy Role][badge-role]][link-galaxy]
[![Downloads][badge-downloads]][link-galaxy]
[![MIT Licensed][badge-license]][link-license]

A brief description of the role goes here.

Requirements
------------

None (except running on a supported OS).<br>
On MacOS: brew.sh should be installed.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

[MIT][link-license]

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

[link-galaxy]: https://galaxy.ansible.com/mayniklas/yubikey_ssh

[//]: # "ansible-galaxy info mayniklas.yubikey_ssh | grep -E 'id: [0-9]' | awk {'print $2'}"
[badge-role]: https://img.shields.io/ansible/role/59221.svg?style=flat-square
[badge-downloads]: https://img.shields.io/ansible/role/d/59221.svg?style=flat-square
[badge-license]: https://img.shields.io/github/license/mayniklas/ansible-yubikey.svg?style=flat-square
[link-license]: https://raw.githubusercontent.com/mayniklas/ansible-yubikey/main/LICENSE
