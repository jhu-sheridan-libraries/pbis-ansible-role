PBIS-Ansible-Role
=========

A role to install PowerBroker Identity Services (open or enterprise)

Requirements
------------

N/A

Role Variables
--------------

- enterprise: (yes/no)
  - Install PBISE or PBISO
  - Default: yes

- pbis_domain: 
  - The domain to join.  MUST BE SET EXTERNALLY (ie. via a vault)

- pbis_join_ou:
  - The OU within the domain to join into. MUST BE SET EXTERNALLY (ie. via a vault)

- pbis_join_user: 
  - The user with join perms. MUST BE SET EXTERNALLY (ie. via a vault)

- pbis_join_pass: 
  - The pass for the above user. MUST BE SET EXTERNALLY (ie. via a vault)

Dependencies
------------

N/A

Example Playbook
----------------

(TODO)

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

TBD

Author Information
------------------

- Derek Belrose (dbelrose@jhu.edu)
- Derek Belrose (derek@derekbelrose.com)
