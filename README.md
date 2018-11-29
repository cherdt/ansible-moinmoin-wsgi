Role Name
=========

This is a work in progress.

A role to install MoinMoin wiki software, running under Apache and mod_wsgi.

Requirements
------------

CentOS (or likely RHEL or Fedora, a target host where the yum module works).

Role Variables
--------------

wsgi_user: a user/group created to run wsgi
wiki_admin_username: a MoinMoin superuser
wiki_admin_password: the MoinMoin superuser password

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

Chris Herdt
https://osric.com/chris/accidental-developer/
