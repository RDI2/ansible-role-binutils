Ansible Role - binutils
==================

This playbook installs [GNU Binutils](https://www.gnu.org/software/binutils/).

Platforms
---------

CentOS 6.7 is the only platform that is supported and tested so far.

Role Variables
--------------

- Check out [defaults/main.yml](defaults/main.yml)

Dependencies
------------

None.

Installation
------------

Regular installation:

```
ansible-galaxy install RDI2.binutils
```

Installation to a specific directory(e.g. roles/):

```
ansible-galaxy install -p roles/ RDI2.binutils
```

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: RDI2.binutils }

License
-------

MIT License.

Author Information
------------------

- Koji Tanaka, RDI2
