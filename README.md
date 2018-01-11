# Meltdown-Spectre-Patch
Meltdown and Spectre Vulnerabilities patch for rhel centos
Spectre / Metdown Patch

Execute the playbook to patch [spectre]/[meltdown] vulnerabilities.

Requirements
------------

There is no requirements

Role Variables
--------------

```yaml
```


Dependencies
------------

There is no dependencies

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - { role: spectre-meltdown-patch }
```

License
-------

BSD

[spectre](https://spectreattack.com/)
[meltdown](https://meltdownattack.com/)
