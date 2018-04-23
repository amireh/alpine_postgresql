alpine_postgresql
=================

Install the latest PostgreSQL available on Alpine along with the `psycopg2`
Python module to be able to run the various Ansible pg_* modules.

Requirements
------------

None.

Role Variables
--------------

None. It will install the latest postgresql available on APK and psycopg2.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: amireh.alpine_postgresql }

License
-------

CC-BY

Author Information
------------------

Ahmad Amireh: ahmad@instructure.com
