Ansible role: Timezone
=========
[![Ansible Role](https://img.shields.io/ansible/role/55683)](https://galaxy.ansible.com/moletti/timezone) [![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/moletti/ansible-role-timezone)](https://github.com/moletti/ansible-role-timezone/releases) [![GitHub Workflow Status](https://img.shields.io/github/workflow/status/moletti/ansible-role-timezone/Ansible%20Molecule?label=test)](https://github.com/moletti/ansible-role-timezone/actions/workflows/molecule.yml) [![Ansible Quality Score](https://img.shields.io/ansible/quality/55683)](https://galaxy.ansible.com/moletti/timezone) [![Ansible Role](https://img.shields.io/ansible/role/d/55683)](https://galaxy.ansible.com/moletti/timezone)

Base role for configure the time zone.

Install
------------
```
ansible-galaxy install moletti.timezone
```

Example playbook
------------
```yaml
- hosts: all
  gather_facts: yes
  vars:
    timezone: "Etc/UTC"
  roles:
    - { role: moletti.timezone, tags: timezone }
```

Role Variables
--------------
|  variable    | type   | default | description                                   |
|--------------|--------|---------|-----------------------------------------------|
| timezone     | str    | Etc/UTC | Name of the timezone for the system clock.    |


LICENSE
-------
[MIT](/LICENSE)