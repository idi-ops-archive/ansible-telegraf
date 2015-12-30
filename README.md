telegraf Ansible role
==============================

Ansible role to configure telegraf for metrics collection.

Role Variables
--------------

See defaults/main.yml

Dependencies
------------

Needs InfluxDB server up and running.

Example Playbook
----------------


    - hosts: localhost
      roles:
         - telegraf

License
-------

MIT
