# Add PHP-FPM base image
FROM php:8.3.4-fpm-alpine3.19

RUN mv "$PHP_INI_DIR/php.ini-production" "$PHP_INI_DIR/php.ini"
COPY www.conf /usr/local/etc/php-fpm.d/www.conf

EXPOSE 9000