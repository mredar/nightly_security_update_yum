nightly_security_updates_aws
========

Create a crontab job to run yum security updates on aws nightly.
Crontab will be run as ansible_ssh_user but must have sudo capability
to install a file to /etc/sudoers.d

Requirements
------------

Must be run from a user which has sudo capacity.

Role Variables
--------------


Dependencies
------------


Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------


