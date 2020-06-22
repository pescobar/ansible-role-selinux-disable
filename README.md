[![Build Status](https://travis-ci.org/pescobar/ansible-role-selinux-disable.svg?branch=master)](https://travis-ci.org/pescobar/ansible-role-selinux-disable)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-pescobar.selinux_disable-blue.svg)](https://galaxy.ansible.com/pescobar/selinux_disable)

pescobar.selinux_disable
=========

Very simple role to disable selinux and reboot the machine.

By default the machine is **not** rebooted unless you define `selinux_disable_reboot: true`

Role Variables
--------------

```
selinux_disable_reboot: false
selinux_disable_reboot_timeout: 600
```

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: pescobar.selinux_disable }

License
-------

BSD

Author Information
------------------

Pablo Escobar
