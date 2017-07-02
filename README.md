Ansible role: configure FusionDirectory to work with 389DS
==========================================================

WIP - Work in progress, don't use this role except if you want to improve it

A role to configure and integrate fusiondirectory with 389DS on centos. (for 
more information about this project please visit the official website 
https://www.fusiondirectory.org)

Requirements
------------
  
  - A working install of FusionDirectory (please have a look to my
    fusiondirectory role)
  - an runing instance of 389DS (you can also check my 389DS role)


Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
