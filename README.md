Monster UI
==========

Monster UI Role for Kazoo Ansible

Requirements
------------

None

Role Variables
--------------

User Variables
- kazoo_domain - The domain used to access Monster UI
- ssl_certificate - The TLS certificate used for the Monster UI domain
- ssl_private_key - The TLS private key used for the Monster UI domain

Dependencies
------------

Roles
- kazoo-ansible.common

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: kazoo-ansible.monsterui, kazoo_domain: kazoo.lan, ssl_certificate: cert, ssl_private_key: key }

License
-------

MIT

