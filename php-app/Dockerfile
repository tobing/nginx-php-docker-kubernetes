FROM php:8.1-apache

RUN docker-php-ext-install mysqli opcache pdo_mysql

COPY index.php /var/www/html

WORKDIR /var/www/html