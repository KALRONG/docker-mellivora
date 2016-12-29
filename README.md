Mellivora for docker
====================

Basic deploy of mellivora in a Debian system.

Important considerations:
-------------------------

This is just the basic deployment of mellivora with the MYSQL DB configured, you still need to configure the different settings for mellivora on its config file.

You need to change the following files as you see necessary:

```
/var/www/mellivora/include/config/config.inc.php
```
```
/etc/apache2/sites-available/mellivora.conf
```
```
/var/www/mellivora/include/config/db.inc.php
```

For more information refer to: https://github.com/Nakiami/mellivora/blob/master/install/README.md

Usage:
-----

```
docker run -d -p 80:80 -p 443:443 kalrong/docker-mellivora
```

Updates:
-------

I will try to keep the mellivora versions as updated as possible, if you want me to update it just open an issue on the github repository and I will run the build asap.
