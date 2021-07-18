Ansible role: Timezone
=========

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