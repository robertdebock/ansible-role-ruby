Role Name
=========

Provides X for your system.

Requirements
------------

Access to a repository containing packages, likely on the internet.

Role Variables
--------------

None known.

Dependencies
------------

- robertdebock.bootstrap

Example Playbook
----------------

```
- hosts: servers

  roles:
    - robertdebock.ROLE

  tasks:
    - name: some task
      copy:
        src: files/somefile
        dest: /some/location
```

License
-------

Apache License, Version 2.0

Author Information
------------------

Robert de Bock <robert@meinit.nl>
