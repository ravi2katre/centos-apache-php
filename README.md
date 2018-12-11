# Supported tags and respective `Dockerfile` links

-   [`latest`] Centos 7 + Apache 2.4 + PHP 5.6
-   [`php7_remi`] Centos 7 + Apache 2.4 + PHP 7.2

# Info
Release based on official [centos] (https://hub.docker.com/_/centos/) images with addition of:

- Apache
- PHP
- PDO
- OCI8
- SQLSRV
- MySQL
- GD

# Run
Run this image:

```console
$ docker run --name centos-apache-php -d cetres/centos-apache-php:php7_remi
```
