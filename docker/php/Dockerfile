FROM phpdockerio/php:8.1-fpm

USER root

RUN apt-get update && \
    apt-get install -y \
    php8.1-imagick \
    php8.1-curl \
    php8.1-zip \
    php8.1-pdo \
    php8.1-xml \
    php8.1-mbstring
