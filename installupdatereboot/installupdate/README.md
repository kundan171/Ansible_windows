Role Name
=========

Windows update installtion and reboot if require  on the server.

Requirements
------------

To Check the avaiable upadte on remote server and perform the installtion on the server and reboot the server once the update is done


Dependencies
------------

installupdate/
├── defaults
│   └── main.yml
├── files
├── handlers
│   └── main.yml
├── meta
│   └── main.yml
├── README.md
├── tasks
│   ├── main.yml
│   └── installupdate.yml
├── templates
├── tests
│   ├── inventory
│   └── test.yml
└── vars
    └── main.yml


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { installupdate }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
kundan singh
