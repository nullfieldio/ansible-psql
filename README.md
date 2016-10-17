psql
=========

Role to install postgres client libraries like psql. Adds postgres repo and installs


Role Variables
--------------

pg_package_name: Name of package in the repo
pg_repo_rpm_url: Url for rpm of postgresql repo

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
      
    - hosts: all 
      roles:
        - role: psql

License
-------

BSD

[![Build Status](https://travis-ci.org/tobybro/ansible-psql.svg?branch=master)](https://travis-ci.org/tobybro/ansible-psql)
