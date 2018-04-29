security role
==============

Description
-----------

This role applies both RHEL7-STIG and RHEL7-CIS.

Defaults
------------
```YAML
rhel7cis_httpd_server: true
rhel7cis_ldap_server: true
rhel7cis_bind: true
rhel7cis_httpd: true
rhel7cis_named_server: true
rhel7cis_host_allow:
  - "0.0.0.0/0"
```

Example
-------

Playbook: Security Hardening

```YAML
---
- name: "Security: Linux Hardening"
  hosts: linux
  become: true

  tasks:
    - name: "victorock.security"
      include_role:
        name: victorock.security
        tasks_from: run
```

Authors
-------

Victor da Costa
