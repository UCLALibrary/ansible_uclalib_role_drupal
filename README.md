UCLALib Drupal Role [![Build Status](https://travis-ci.org/UCLALibrary/uclalib_role_template.svg?branch=master)](https://travis-ci.org/UCLALibrary/uclalib_role_drupal)
=========

This role is still in heavy development. By default with running an example playbook in tests/defaultplaybook.yml, it'll install

RHEL/CentOS SCLs
PHP 7.0 and dependencies
MySQLClient 5.6.32
Drush 8
Composer

Optional(run other playbook tests/siteurldefinedplaybook.yml)
HTTPS

Requirements
------------

CentOS 6 or RHEL 6

Role Variables
--------------

- siteurl: test-seniorfellows.library.ucla.edu
-- This will also set up SSL with associated cert/key pair. Not recommended for local dev unless you know what you're doing.
- default siteurl: localdev.local
  - This will also set up SSL with associated cert/key pair. Not recommended for local dev unless you know what you're doing.

default siteurl: localdev.local

Dependencies
------------
- SCL
- UCLALib Yum repo for MySQL package

Example Playbook
----------------
See playbooks in tests directory

License
-------

BSD 3-Clause

Author Information
------------------
Written by Casey Grzecka and Anthony Vuong from UCLA Library