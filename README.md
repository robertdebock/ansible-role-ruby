ruby
=========

[![Build Status](https://travis-ci.org/robertdebock/ansible-role-ruby.svg?branch=master)](https://travis-ci.org/robertdebock/ansible-role-ruby)

Provides Ruby for your system.

Requirements
------------

Access to a repository containing packages, likely on the internet.

Role Variables
--------------

None known.

Dependencies
------------

- robertdebock.bootstrap

Download the dependencies by issuing this command:
```
ansible-galaxy install --role-file requirements.yml
```

Example Playbook
----------------

```
- hosts: servers

  roles:
    - robertdebock.ruby
```

Install this role using `galaxy install robertdebock.ruby`.

License
-------

Apache License, Version 2.0

Author Information
------------------

Robert de Bock <robert@meinit.nl>
