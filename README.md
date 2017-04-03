[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-emacs-daemon-supervisord.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-emacs-daemon-supervisord)
andrewrothstein.emacs-daemon-supervisord
=========

Installs a supervisord program specification for an emacs daemon

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
    - andrewrothstein.supervisord
    - andrewrothstein.emacs-daemon-supervisord
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
