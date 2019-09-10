FROM php:7.3.9-fpm-alpine
RUN apt-get update
RUN apt-get install libpng libpng-devel
RUN docker-php-ext-install gd \
    && docker-php-ext-install pdo_mysql