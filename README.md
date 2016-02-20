varnish
=======

Installs Varnish

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

| Name            | Default | Description                   |
|-----------------|---------|-------------------------------|
| varnish_version | 4.0.3   | Version of Varnish to install |

Dependencies
------------

None

Example Playbook
----------------

Install Varnish
```yaml
- hosts: all
  roles:
    - kbrebanov.varnish
```

Install older version of Varnish
```yaml
- hosts: all
  roles:
    - { role: kbrebanov.varnish, varnish_version: 3.0.5 }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
