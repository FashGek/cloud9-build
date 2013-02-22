Cloud9 IDE Build
================

Cloud9 IDE built for Ubuntu 12.04.

Building the IDE takes a long time, and we want to cut down on server provisioning time, so we instead deploy this pre-built version.

To build, run the Ansible playbook called build-cloud9.yml on an Ubuntu machine:

    ansible-playbook -c local build-cloud9.yml
