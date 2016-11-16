drupal-backup
=============

Drupal-backup is an Ansible role that performs a backup of a Drupal site.

It has the following advantages:
* No need for Drush or modules like Backup and Migrate.
* Works on multiple versions of Drupal.
* Automatically deletes old backups given a configurable period.
* Option to fetch the backup from a remote location when run.
* Option to upload the backup to Amazon S3 when run.

Requirements
------------

* Ansible 2.0 or higher.
* boto
* MySQLdb, mysqldump
* tar, gzip

Role Variables
--------------

TBD.

Dependencies
------------

TBD.

Example Playbook
----------------

TBD.

License
-------

BSD

Author Information
------------------
