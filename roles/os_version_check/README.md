OS Version Check
=========

This role obtains and prints the OS Family, Distribution and version.

Example Playbook
----------------


```yaml

    - name: Check OS Info
      hosts: all
      roles:
         - { role: itblaked.general.os_version_check }

```

License
-------

BSD

Author Information
------------------

Blake Douglas
