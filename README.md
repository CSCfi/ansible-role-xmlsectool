[![Build Status](https://travis-ci.org/CSCfi/ansible-role-xmlsectool.svg?branch=master)](https://travis-ci.org/CSCfi/ansible-role-xmlsectool)

Ansible-Role: xmlsectool
=========

An role which installs xmlsectool on RedHat/Debian servers.

Requirements
------------

* JAVA

Role Variables
--------------

See defaults/main.yml for the variables you can overwrite via role call via parameter

* xmlsectool_version: 2.0.0
* xmlsectool_path: /opt

Dependencies
------------

* None

Example Playbook
----------------

    - hosts: all
      roles:
        - { role: CSCfi.xmlsectool }

