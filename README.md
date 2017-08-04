[![Build Status](https://travis-ci.org/thomaslorentsen/ansible-git-client.svg?branch=master)](https://travis-ci.org/thomaslorentsen/ansible-git-client)
[![Ansible Role](https://img.shields.io/ansible/role/19713.svg)](https://galaxy.ansible.com/thomaslorentsen/ansible-git-client/)

Ansible Git Client
=========

Installs the git client with some configuration

Vars
------------

A list of optional vars that can be passed into the role for configuration


| Var | Description |
| --- | --- |
| ```git_name``` | Git Username |
| ```git_email``` | Git Email Address |
| ```git_email``` | Git Email Address |
| ```git_signingkey``` | Git PGP Key |

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: thomaslorentsen.ansible-git-client, git_name: "username", git_email: "email@address.com" }

License
-------

BSD

Author Information
------------------

- [GitHub](https://github.com/thomaslorentsen)
