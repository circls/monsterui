Monster UI
==========

Kazoo Ansible Role for Monster UI

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

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: kazoo-ansible.monsterui, kazoo_domain: kazoo.lan, ssl_certificate: cert, ssl_private_key: key }

License
-------

MIT

