FROM ozconseil/php:5.6-apache
MAINTAINER ozconseil <dev@ozconseil.com>

COPY xdebug.ini /usr/local/etc/php/conf.d/xdebug.ini
RUN pecl install xdebug-2.5.5 && docker-php-ext-enable xdebug
