my-ansible
---

# Introduction
This is an Ansible playbook for PHP and AngularJS development. It installs Apache+MySQL for PHP and node for running npm, yo and grunt.
It also includes my dotfiles and is adapted to my directory structure, so be sure to create ~/Projects/www folder on the host machine


# Host machine information
`~/Projects folder is linked as /vagrant on VM`
`~/Projects/www folder is linked as /var/www on VM`

This allows me to have different Virtual Machines which will share the same www folder so I can test applications on different verions of software.


# Installed software

**Services:**

Apache, MySQL, Memcached

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


# TODO
- Add project generators
- Improve README to explain how to use different verions of software