hdp-knox-test
=========

This is an ansible role with the purpose of testing successful integration of
the Hadoop Ecosystem component Apache Knox.

Requirements
------------

Of course you need a fully set-up and Knox secured Hortonworks Dataplatform,
that you want to test.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: condla.hdp-knox-test}

License
-------

BSD

Author Information
------------------

Stefan Kupstaitis-Dunkler (stefan.dun@gmail.com)
