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

Development
-----------

Poetry is used to manage this project's Python dependencies

### Installation
`poetry install --no-root`

### Running
`poetry run molecule test`

Alternative, you can create a shell by running `poetry shell` and run the `molecule` commands directly

License
-------

MIT

