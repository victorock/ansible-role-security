security role
==============

Description
-----------

This role applies both RHEL7-STIG and RHEL7-CIS.

Defaults
------------

rhel7cis_httpd_server: true
rhel7cis_ldap_server: true
rhel7cis_bind: true
rhel7cis_httpd: true
rhel7cis_named_server: true
rhel7cis_host_allow:
  - "0.0.0.0/0"

Authors
-------

Victor da Costa
