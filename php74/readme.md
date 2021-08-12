# PHP 7.4 Ansible configuration by marlek

Check out readme.md in the root of the repository for prerequisites and installation guide.

## Installed software

**Debian 9 (Stratch)**

### Services
Apache 2.4, MySQL 5.7, Redis 3.2, Memcached, Supervisor

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

**Version**: 7.4

**Modules**: php7.4-cli, php7.4-common, php7.4-curl, php7.4-dev, php7.4-gd, php7.4-imap, php7.4-intl, php7.4-json, php7.4-mcrypt, php7.4-mysql, php7.4-opcache, php7.4-pgsql, php7.4-readline, php7.4-sqlite3, libapache2-mod-php7.4, php7.4-xml, php7.4-zip, php-redis

### Node

**Version**: 10

**Packages**: grunt-cli, gulp, yo
