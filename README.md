Role Name
=========

This is a work in progress. It does a lot of less-than-ideal things.

A role to install [MoinMoin](http://moinmo.in/) wiki software, running under Apache and mod_wsgi.

Requirements
------------

CentOS (or likely RHEL or Fedora, a target host where the firewalld, systemd, and yum modules work).

Role Variables
--------------

* wsgi_user: a user/group created to run wsgi
* wiki_admin_username: a MoinMoin superuser
* wiki_admin_password: the MoinMoin superuser password
* wiki_admin_email: the email address of the MoinMoin superuser

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

    - hosts: wikihosts
      roles:
         - ansible-moinmoin-wsgi

After running the playbook, visit http://mywiki.example.com/LanguageSetup?action=language_setup to install help pages for the language of your choice.

License
-------

???

Author Information
------------------

Chris Herdt
https://osric.com/chris/accidental-developer/
