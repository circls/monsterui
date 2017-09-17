MonsterUI
=========

Kazoo Ansible role for Monster UI

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

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: kazoo-ansible.monsterui, kazoo_domain: kazoo.lan, ssl_certificate: cert, ssl_private_key: key }

License
-------

MIT

