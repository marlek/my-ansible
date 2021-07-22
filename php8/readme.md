# PHP 8 Ansible configuration by marlek

Check out readme.md in the root of the repository for prerequisites and installation guide.

## Installed software

**Ubuntu 20.04 (Focal Fossa)**

### Services
Apache 2.4, MariaDB 10.4, Redis 6.2.4, Memcached, Supervisor

### System packages

curl, wget, python-software-properties, vim, git, htop, unzit, etc.

### Apache

**Version**: 2.4

**Modules**: rewrite, vhost_alias, headers, expires, filter

### MySQL

**Version**: MariaDB 10.4

**Root user**: root

**Root pass**: root

### PHP

**Version**: 8.0

**Modules**: php8.0-cli, php8.0-common, php8.0-curl, php8.0-dev, php8.0-gd, php8.0-imap, php8.0-intl, php8.0-mcrypt, php8.0-mysql, php8.0-opcache, php8.0-pgsql, php8.0-readline, php8.0-sqlite3, libapache2-mod-php8.0, php8.0-xml, php8.0-zip, php-redis

### Node

**Version**: 14
