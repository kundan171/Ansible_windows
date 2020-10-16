Role Name
=========

Add registry entries to endpoints to configure automatic updates settings

Requirements
------------

the WSUS server in the test environment. This value has to be modified with the name of the WSUS server used in the production environment.

Role Variables
--------------

├── addregistry
|   |__meta
|   |
│   ├── README.md
│   ├── tasks
│   └── vars
├── Addregit.log
├── hosts
├── playbook.retry
└── playbook.yml


Dependencies
------------

The Dependencies in the playbook is regarding the tasks and vars .
vars is having the requirement for adding the Result file in the controller server.


|___ addregistry
│   ├── tasks
│   └── vars
├── hosts
├── playbook.retry
└── playbook.yml

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: addregistry.yml,  }

License
-------

BSD

Author Information
------------------

Kundan singh
kundsing7368@in.ibm.com
