Symfony 2.2 Skeleton
====================

This is a standard Symfony Skeleton cookbook that has the AcmeBundle
removed to get started with your own pages instantly. I am using this
Repository so I don't have to re-do the basic setup steps all the time
to get the Bundle removed.

Installation
------------

Clone this repository and run the following commands:

```
curl -s http://getcomposer.org/installer | php
php composer.phar install
sudo setfacl -R -m u:www-data:rwX -m u:`whoami`:rwX app/cache app/logs
sudo setfacl -dR -m u:www-data:rwx -m u:`whoami`:rwx app/cache app/logs
```

Once configured and linked to your Webserver (`ln -s` will do) you can
access the configurator to setup some basic parameters:

* http://localhost/yoursymlink/app_dev.php/_configurator
