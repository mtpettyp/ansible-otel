[![CircleCI](https://circleci.com/gh/mtpettyp/ansible-otel.svg?style=svg)](https://circleci.com/gh/mtpettyp/ansible-otel)



Open Telemetry
==============

Open Telemetry role


Role Variables
--------------
* `prometheus_admin_password` - Password for admin user of Prometheus

Example Playbook
----------------

```yaml
- hosts: all
  vars:
    prometheus_admin_password: password
  include_role:
    name: "ansible-otel"
```


License
-------

MIT

