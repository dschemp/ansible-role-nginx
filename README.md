Ansible Role: nginx
=========

An Ansible role for deploying Nginx.

Role Variables
--------------

See [`defaults/main.yml`](defaults/main.yml).

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: nginx
  become: true
  roles:
    - role: dschemp.nginx
```

License
-------

MIT
