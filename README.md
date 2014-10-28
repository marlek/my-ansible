my-ansible
---

# Introduction
This is an Ansible playbook for PHP and AngularJS development. It installs Apache+MySQL for PHP and node for running npm, yo and grunt.
It also includes my dotfiles and is adapted to my directory structure, so be sure to create ~/Projects/www folder on the host machine


# Host machine information
`~/Projects folder is linked as /vagrant on VM`
`~/Projects/www folder is linked as /var/www on VM`

This allows me to have different Virtual Machines which will share the same www folder so I can test applications on different versions of software.

# Prerequisites

[VirtualBox](https://www.virtualbox.org)

[Vagrant](https://www.vagrantup.com)

[Ansible](http://www.ansible.com) (Easiest to install via `homebrew` or something similar)

# Installed software

**Ubuntu 12.04 (Precise Pangolin)** (I don't use latest Ubuntu because of PHP 5.4)

**Services:**

Apache, MySQL (5.5), Memcached

**System packages:**

curl, wget, python-software-properties, vim, git, imagemagick, htop

**Apache modules:**

rewrite, vhost_alias, headers, expires, filter

**PHP:**

Version: 5.4

Modules: php5-cli, php5-curl, php5-imagick, php5-mcrypt, php5-mysql, php5-memcached, php5-sqlite, php5-xdebug

Tools: composer

**Node:**

Version: 0.10.*

Packages: grunt-cli, gulp, yo, bower

# Installing different versions of software

**PHP**

In order to install different version of PHP you need to change `php_ppa` variable in `ansible/vars/common.yml` file:

For PHP **5.4**: `php5-oldstable`

For PHP **5.5**: `php5`

For PHP **5.6**: `php5-5.6`

**MySQL**

In order to install MySQL 5.6 instead of default 5.5 change `mysql_56` variable in `ansible/vars/common.yml` file:

`mysql_56: true`

# TODO
- Add project generators
