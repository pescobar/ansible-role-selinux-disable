ansible-role-selinux-disable
=========

Very simple role to disable selinux and reboot the machine.

By default the machine is not rebooted unless you define `selinux_reboot: true`

Role Variables
--------------

```
selinux_reboot: false
selinux_reboot_timeout: 600
```

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: pescobar.selinux-disable }

License
-------

BSD

Author Information
------------------

Pablo Escobar
