deb-maintainer
=========

Installes Debian packaging packages and configures DEBEMAIL and DEBFULLNAME

Requirements
------------

My [zsh role](https://github.com/ThreeFx/ansible-zsh).

Role Variables
--------------

| Variable Name | Default Value | Description |
--------------- |---------------|--------------
`deb_maintainer_email` | "" | required, valid E-Mail for DEBEMAIL
`deb_maintainer_fullname` | "" | required, your name

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: deb-maintainer
           vars:
             deb_maintainer_email: "foo@bar.com"
             deb_maintainer_name: "Foo Quux Bar"

License
-------

BSD

Author Information
------------------

Find me on [GitHub](https://github.com/ThreeFx).
