Ansible Role: BIND
=========

Installs BIND on RHEL/CentOS, Debian/Ubuntu & OpenSUSE Servers

Requirements
------------

- A named.conf in the `templates` folder
- All your zone files in the `files/zones` folder.

Role Variables
--------------

There are no variables for this role

Dependencies
------------

There are no dependencies for this role.

Example Playbook
----------------

```yaml
- hosts: bind
  become: true
  roles:
    - role: jamdoog.bind
```

License
-------

BSD

Author Information
------------------

This role was created by James Ledger, I write about things on https://jamesledger.net

