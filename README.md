Role Name
=========

Configuring time zones and NTP services.  Needed in AWS EC2 environments.

Requirements
------------

TODO

Role Variables
--------------

* time_install: true
* time_timezone: UTC

Dependencies
------------

* kurron.base

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.time, time_timezone:  America/New_York }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
