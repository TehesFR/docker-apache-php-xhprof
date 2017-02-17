# About this repo

**Drupal** optimized images for apache-php with **xhprof**.

This container should not be your main development container, and should only be used when you need to have profiling data of a page.
Use [this container](https://github.com/TehesFR/docker-apache-php) for your main development container.

Available tags are:
- 7.0, latest ([7.0/Dockerfile](https://github.com/TehesFR/docker-apache-php-xhprof/tree/master/7.0/Dockerfile))
- 5.6 ([5.6/Dockerfile](https://github.com/TehesFR/docker-apache-php-xhprof/tree/master/5.6/Dockerfile))

The image basically contains:

- All php libraries needed for Drupal (gd, mbstring, mcrypt, zip, soap, pdo_mysql, mysqli, xsl, opcache, calendar)
- Xhprof profiling tool which will store profiling data of every page you browse in a mongodb container

# Docker-compose

Please check our complete docker-compose.yml example at: https://github.com/TehesFR/docker-apache-php

[Docker Hub page](https://hub.docker.com/r/tehes/docker-apache-php-xhprof/)
