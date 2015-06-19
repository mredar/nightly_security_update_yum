nightly_security_update_yum
========

Create a crontab job to run yum security updates nightly.
For systems with yum as their package manager
Crontab will be run as ansible_ssh_user but must have sudo capability
to install a file to /etc/sudoers.d
Developed for AWS Linux AMI.

Requirements
------------

Must be run from a user which has sudo capacity.

Role Variables
--------------


Dependencies
------------

yum

Example Playbook
-------------------------

- hosts: servers
  roles:
    - { role: nightly_security_update_yum }

License
-------

BSD

Author Information
------------------


