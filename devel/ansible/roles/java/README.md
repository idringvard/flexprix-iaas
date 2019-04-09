Java
=========

Role responsible for installing OpenJDK 11 on target machine

Requirements
------------

No special requirements, can run on any Linux host

Role Variables
--------------

openjdk_tarball - name of tarball file containing distribution
openjdk_url - URL to download OpenJDK from
openjdk_directory - Target directory where to install JDK, JDK foder will be installed to this directory

Dependencies
------------

No dependencies

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: java }

License
-------

MIT

