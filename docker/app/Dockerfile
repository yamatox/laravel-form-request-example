FROM php:7-fpm

RUN apt-get update && apt-get install -y zip unzip && \
    curl -sS https://getcomposer.org/installer | php && \
    mv composer.phar /usr/local/bin/composer

