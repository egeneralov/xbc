egeneralov.xbc
==============

Provision Bitcoin Plus (xbc) node. Will be exposed to *:3517.

Requirements
------------

Debian-based system

Role Variables
--------------

- **version**: `2.7.0`
- **rpcuser**: `test`
- **rpcpassword**: `test`
- **datadir**: `/var/lib/bitcoinplus/`

Example Playbook
----------------

    - hosts: nodes
      vars:
        version: 2.7.0
        rpcuser: test
        rpcpassword: test
        datadir: /var/lib/bitcoinplus/
      roles:
         - egeneralov.xbc

License
-------

MIT

Author Information
------------------

Eduard Generalov <eduard@generalov.net>
