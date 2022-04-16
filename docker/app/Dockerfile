FROM php:7.0-fpm

RUN apt-get update
RUN apt-get install -y libmcrypt-dev mysql-client curl zip unzip
RUN docker-php-ext-install mcrypt pdo_mysql

WORKDIR /var/www
