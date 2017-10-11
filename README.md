# ansible-role-mongo
Ansible role for installing and configuring MongoDB

Requirements
------------

Instance with ubuntu 16.04

Role Variables
--------------

`mongo_bind_ip: 127.0.0.1` - MongoDB IP address. Default: `127.0.0.1`

`mongo_port: 27017` - MongoDB port. Default: `27017`

`env` - current environment (stage|prod)

Usage
-----

```
- hosts: mongo
  roles:
     - { role: ansible-role-mongo }
```

License
-------

BSD