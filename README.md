andrewrothstein.kpt
=========

![Build Status](https://github.com/andrewrothstein/ansible-kpt/actions/workflows/build.yml/badge.svg)

Installs the [kpt](https://kpt.dev/) cli

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
    - andrewrothstein.kpt
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
