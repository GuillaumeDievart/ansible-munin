Ansible Munin
=============

Install and configure munin on Debian server.

Installation
------------

git submodule add git@github.com/boostmyshoporganization/ansible-munin roles/munin

```yaml
roles:
    - munin
```

Configuration
-------------

```yaml
munin:
  hosts:
    - { name: 'test', group: 'test', ip: 'localhost' }
  contacts:
    - { name: 'gdievart', email: 'gdievart@example.com' }
    - { name: 'sklein', email: 'sklein@example.com' }
```