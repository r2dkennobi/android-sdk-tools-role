android-sdk-tools
=========

Just another Android SDK tools role

Also installs "platform-tools" and "tools" using `sdkmanager`

![Build Status](https://travis-ci.org/r2dkennobi/android-sdk-tools-role.svg?branch=master)

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: r2dkennobi.android-sdk-tools }

or to run locally

    $ ansible-playbook -i tests/inventory tests/test.yml --connection=local

Note: Assumes `ansible.cfg` exists in the root of the repo with the following content:

    [defaults]
    roles_path = ../

License
-------

GPL
