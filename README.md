recap
=========

Ansible role to install & configure [recap](https://github.com/rackerlabs/recap/)

Requirements
------------

- ansible_os_family=RedHat (i.e. redhat, centos, amazon linux, oracle, ...)
- [EPEL](https://fedoraproject.org/wiki/EPEL)
- Ansible (tested with 2.4.0.0 but should work with any)

Role Variables
--------------

TODO:
- [ ] support variables for configuration
- [ ] support variables for crontab scheduling

Dependencies
------------

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: seanorama.ansible-recap }
```

<!--
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
    - hosts: servers
      roles:
         - { role: seanorama.ansible-recap, x: 42 }
-->

License
-------

BSD

Author Information
------------------

Sean Roberts
- http://github.com/seanorama
- http://twitter.com/seano
