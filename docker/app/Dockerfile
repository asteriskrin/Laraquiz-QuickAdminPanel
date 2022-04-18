FROM php:7-fpm

RUN apt-get update
RUN apt-get install -y libmcrypt-dev curl zip unzip
RUN pecl install mcrypt-1.0.4
RUN docker-php-ext-enable mcrypt
RUN docker-php-ext-install mysqli pdo pdo_mysql

WORKDIR /var/www
