andrewrothstein.ssh-client
===========================
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-ssh-client.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-ssh-client)

Installs ssh client tooling

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.ssh-client
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
