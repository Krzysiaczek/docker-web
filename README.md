# docker-web
Mainly container for Dockerfile(s) to extend php-apache docker images

Image location: https://hub.docker.com/r/krzysiaczek/web/

Important files
---------------

- Dockerfile.web.5.6 -> base (1.0) based on php:5.6-apache
- Dockerfile.wev.1.01 -> update of the base with additional installation of PHP Composer, Git and zip extension required by internal process of Symfony installation
