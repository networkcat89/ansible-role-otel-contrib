Role Name
=========

**otel_collector**

Requirements
------------

none

Role Variables
--------------
*defaults:*

otelcol_version: ""

jaeger_endpoint: ""

loki_endpoint: ""

*vars:*

_otel_binary_install_dir: ""

Dependencies
------------

- prometheus
- jaeger
- loki

Example Playbook
----------------

    - hosts: servers
      roles:
         - otel_collector

License
-------

BSD 3-Clause License

Author Information
------------------

Viacheslav Lochashvili
