Ansible Role: For web python application
========================================

Ansible Role that download web-app docker image and run container

Requirements
------------

none

Role Variables
--------------


Dependencies
------------

Uses role docker from git@github.com:teralex79/exam-ansible-docker-role.git

```yaml
- name: Run role Install Docker
  include_role:
    name: docker
```

Example Playbook
----------------

```yaml
- hosts: web 
  roles:
    - { role: web-app }
```

License
-------

BSD

Author Information
------------------
This role was created in 2019 by Aleksei Terentev for DevOps Exam
