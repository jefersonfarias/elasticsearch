# elasticsearch
========

Ansible role for installing and configuring a basic ElasticSearch.

Requirements
------------

none
------------

Example Playbook
-------------------------

---
```
- name: elasticsearch-server
  hosts: all
  sudo: true

  roles:
    - { role: elasticsearch }
```
