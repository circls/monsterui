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
- kazoo_enable_lets_encrypt - Enables Let's Encrypt TLS certificate generation if True. Use user supplied TLS certificate if False. False by default.
- kazoo_tls_certificate - The TLS certificate used for the Kazoo domain. Used if Let's Encrypt is disabled.
- kazoo_tls_private_key - The TLS private key used for the Kazoo domain. Used if Let's Encrypt is disabled.
- kazoo_version - The Kazoo version to install from the 2600hz repo. kazoo-ansible manages the version by default.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: kazoo-ansible.monsterui, kazoo_domain: kazoo.lan, kazoo_enable_lets_encrypt: True }

License
-------

MIT

