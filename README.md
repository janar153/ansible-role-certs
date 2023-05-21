Ansible Role: Let's Encrypt Certificates
=========

With this Ansible role you can get TLS certificates from Let's Encrypt
  
Example requirements.yml
------------------------

```
---
- src: https://github.com/janar153/ansible-role-certs.git
  scm: git
  version: main
  name: certs

```


Example Playbook
----------------

```
- hosts: all
  gather_facts: true
  become: true

  roles:
    - role: certs
```

License
-------

MIT
