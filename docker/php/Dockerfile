FROM php:8.2-fpm

ARG userId=1000

RUN docker-php-ext-install pdo_mysql

RUN usermod -u $userId www-data
USER www-data