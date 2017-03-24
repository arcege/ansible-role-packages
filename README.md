Packages
========

Install or uninstall packages, using either apt, yum or pip.

Requirements
------------

Assumes gather\_facts==true to determine OS/flavor.

Role Variables
--------------

default\_packages = list of package names to install, default is an empty list
remove\_packages = list of package names to uninstall, default is an empty list
python\_packages = list of module names to install, default is an empty list
user\_pip = boolean to determine if the pip modules install in the user or system locations

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: packages, python\_packages: ["numpy"] }

License
-------

GPLv3

Author Information
------------------

Michael P. Reilly <http://bitbucket.org/Arcege>
