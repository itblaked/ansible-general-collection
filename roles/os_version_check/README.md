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

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
