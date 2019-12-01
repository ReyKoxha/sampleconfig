# sampleconfig
This repository contains a few example configs, which are supposed to help beginners, who are struggeling with their setup.
As of now the repo contains config files for
- NGINX
  - WordPress
  - NextCloud
  - NodeBB
  - Static website (e.g. Hexo)
  - OnlyOffice Server
- PHP-FPM
- Memcached

Please note that the default user for NGINX, PHP-FPM and Memcached is `www-data`.<br>
You may change it to any user you like.

If you decide to do that, keep in mind that it might be required to regain permissions for your PHP sessions,
after performing a PHP update!
To do so run `chown -R www-data:www-data /var/lib/php`.
