ARG PHP_VERSION="7.4.0"
FROM php:${PHP_VERSION:+${PHP_VERSION}-}fpm-alpine

RUN apk update; \
    apk upgrade;

RUN docker-php-ext-install mysqli
