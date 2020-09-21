ansible-scan-jboss
=========

Ansible module scans for deployed JBoss instances by searching for the jboss-modules.jar and run.jar files and then extracts the version from the pom.properties and MANIFEST.MF, respectively, to determine which distribution contained the jar.

NB: This script is up to date through EAP 6.4 CP23, EAP 7.0 CP09, EAP 7.1 CP06, EAP 7.2 CP09, EAP 7.3 CP02, and WildFly 20.0.1.Final

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

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
