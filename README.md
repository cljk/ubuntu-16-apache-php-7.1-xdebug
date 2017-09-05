```
docker pull vgbpowertech/ubuntu-16-apache-php-7.1-xdebug
```

Based on
* https://github.com/1and1internet/ubuntu-16-apache-php-7.1
* https://github.com/1and1internet/ubuntu-16-apache
* https://github.com/1and1internet/ubuntu-16

Modifications
* Enables mod_rewrite
* overwrites composer with new version
* installs several php-modules (xdebug, tidy, mbstring, gd, xml, mcrypt, curl, intl, ...)
* installs git, subversion, nodejs, htop and mc (just for admin help)
* enables xdebug (beware: with remote_enable on and remote_connect_back on - potential security risk)
* enables opcache with file_cache and for cli
