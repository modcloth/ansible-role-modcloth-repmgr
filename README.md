repmgr-master
=========

This role installs and configures repmgr on a master node and configures replication.

Requirements
------------

Assumes PostgreSQL is already installed and running.

You should have the `include_dir` directive set in your `postgresql.conf`. See the `repmgr_postgresql_conf` default.

Role Variables
--------------

See defaults/main.yml

Dependencies
------------

None

Example Playbook
----------------

```yml
- hosts: servers
  roles:
  - role: modcloth.repmgr-master
```

License
-------

MIT

Author Information
------------------

ModCloth Inc.
