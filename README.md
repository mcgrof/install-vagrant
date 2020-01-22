install-vagrant
===============

The ansible install-vagrant role lets you get install vagrant, and on Linux
also installs the vagrant-libvirt plugin.

Requirements
------------

Run a supported OS/distribution:

  * SUSE SLE / OpenSUSE
  * Red Hat / Fedora
  * Debian / Ubuntu

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Below is an example playbook, say a bootlinux.yml file:

```
---
- hosts: localhost
  roles:
    - role: mcgrof.install-vagrant
```

License
-------

GPLv2
