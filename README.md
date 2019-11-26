CIS-Benchmarks-Hardening-Linux
=========

This role is what I use to harden Linux Systems based off the Center of Internet Security Benchmarks. This currently works for CentOS but will work for Ubuntu and other distros in the future
------------

Requirments for the Ansible Management Server is just to have Ansible, and a connection to the servers that you would like to provision

Role Variables
--------------
The role works by searching for your distro and using the variables list that matches to run the benchmarks against it


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - CIS-Benchmarks-Hardening-Linux

Author Information
------------------
To learn more about me go to anthonyhanna.com and take a look at my Resume. I am a College student just picking up projects to get some experience. Feel free to reach out and talk about tech. 


Note
------------------
Some implementations (ex. firewall rules, partitioning etc.) will need manual intervention to finish hardening
Section 3.6
Section 4.1.12
Section 4.2.1.2
Section 4.2.1.4
