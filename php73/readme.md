# PHP 7.3 Ansible configuration by marlek

Check out readme.md in the root of the repository for prerequisites and installation guide.

## Installed software

**Debian 8 (Jessie)**

### Services
Apache 2.4, MariaDB 10.0, Redis 3.2, Memcached, Supervisor

### System packages

curl, wget, python-software-properties, vim, git, htop, imagemagick

### Apache

**Version**: 2.4

**Modules**: rewrite, vhost_alias, headers, expires, filter

### MySQL

**Version**: MySQL 5.7

**Root user**: root

**Root pass**: root

### PHP

**Version**: 7.3

**Modules**: php7.3-cli, php7.3-common, php7.3-curl, php7.3-dev, php7.3-gd, php7.3-imap, php7.3-intl, php7.3-json, php7.3-mcrypt, php7.3-mysql, php7.3-opcache, php7.3-pgsql, php7.3-readline, php7.3-sqlite3, libapache2-mod-php7.3, php7.3-xml, php7.3-zip, php-redis

### Node

**Version**: 10

**Packages**: grunt-cli, gulp, yo
