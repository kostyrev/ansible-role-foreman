foreman
=========

No time to write DOCs.
See Example Playbook

Requirements
------------

this role doesn't configure
 - PostgreSQL
 - apache (only vhost for foreman)

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

    - hosts: foreman
      vars:
        foreman_version: 1.9
        foreman_ssl: true
        foreman_servername: "{{ ansible_nodename }}"
        foreman_admin_password: 8t2rQKk_xrV
        foreman_oauth_consumer_key: cyyZbb2Wnr
        foreman_oauth_consumer_secret: w5Zz_AMT17
        foreman_db_password: dBzknszf
      roles:
         - { role: kostyrevaa.foreman }

License
-------

BSD

## Contributing

 Send your suggestions and pull requests to https://github.com/kostyrevaa/ansible-role-foreman

 When send PR make sure your changes are backward-compatible.


Author Information
------------------

Aleksandr Kostyrev

