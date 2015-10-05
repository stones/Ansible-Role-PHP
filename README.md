# Ansible PHP Role

***Ubuntu Only (currently)***

In order to utilise PHP on a server, this role installs 5.6



#### Steps taken
- Add repo for PHP 5.6
- install php, cli curl, fpm, gd, imagick, mcrypt, mysql, sqlite, xcache, xmlrpc
- Configure the PHP-FPM ini
- Add root user
- Enable Mcrypt

#### Variables

Example:

```
php_upload_max_filesize: "20M"
php_post_max_size: "20M"
php_memory_limit: "384M"
```

#### Todo
- Make multi-distribution
- Extend the customisable options
- Customise which modules to install
