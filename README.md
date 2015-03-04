
Role to install and configure IPTABLES on RedHat and Debian based systems.
This role has been tested on the following OSs:
--CentOS 6.5
--Ubuntu 12.04 

Requirements
------------

None

Role Variables
--------------

OS specific variables are defined in /vars/{{ ansible_os_family }}.yml files. 
Default variables are defined in /defaults/main.yml
You can open individual ports for the IPTABLES by entering the port values in /defaults/main.yml

Dependencies
------------

None

Example Playbook
----------------

    - hosts: all
      roles:
         - iptables

License
-------

BSD

Author Information
------------------

This role was authored by Yohan | 2015.

