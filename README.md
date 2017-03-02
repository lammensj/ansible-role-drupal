# Ansible Role: Drupal

[![Build Status](https://travis-ci.org/geerlingguy/ansible-role-drupal.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-drupal)

Builds and installs [Drupal](https://drupal.org/), an open source content management platform.

## Requirements

Drupal is a PHP-based application that is meant to run behind a typical LAMP/LEMP/LEPP/etc. stack, so you'll need at least the following:

  - Apache or Nginx (Recommended: `geerlingguy.apache` or `geerlingguy.nginx`)
  - MySQL or similar Database server (Recommended: `geerlingguy.mysql` or `geerlingguy.postgresql`)
  - PHP (Recommended: `geerlingguy.php` along with other PHP-related roles like `php-mysql`).

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    TODO.

## Dependencies

N/A

## Example Playbook

    - hosts: servers
      vars_files:
        - vars/main.yml
      roles:
        - geerlingguy.drupal

*Inside `vars/main.yml`*:

    TODO.

## License

MIT / BSD

## Author Information

This role was created in 2014 by [Jeff Geerling](https://www.jeffgeerling.com/), author of [Ansible for DevOps](https://www.ansiblefordevops.com/).
