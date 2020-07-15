# PHP 7.2 Ansible configuration by marlek

Check out readme.md in the root of the repository for prerequisites and installation guide.

## Installed software

**Debian 9 (Stretch)**

### Services
Apache 2.4, MariaDB 10.0, Redis 3.2, Memcached, Supervisor

### System packages

curl, wget, python-software-properties, vim, git, htop, imagemagick

### Apache

**Version**: 2.4

**Modules**: rewrite, vhost_alias, headers, expires, filter

### MySQL

**Version**: MariaDB 10.0

**Root user**: root

**Root pass**: root

### PHP

**Version**: 7.2

**Modules**: php7.2-cli, php7.2-common, php7.2-curl, php7.2-dev, php7.2-gd, php7.2-imap, php7.2-intl, php7.2-json, php7.2-mcrypt, php7.2-mysql, php7.2-opcache, php7.2-pgsql, php7.2-readline, php7.2-sqlite3, libapache2-mod-php7.2, php7.2-xml, php7.2-zip, php-redis

### Node

**Version**: 8

**Packages**: grunt-cli, gulp, yo
