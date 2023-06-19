# load php 8.2 base image
FROM php:8.2-fpm-alpine

# install dependencies
RUN docker-php-ext-install pdo_mysql mysqli bcmath

# Set working directory
WORKDIR /var/www/html/

# Expose port 9000
EXPOSE 9000