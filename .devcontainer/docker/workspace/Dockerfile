FROM php:alpine3.17

ENV COMPOSER_ALLOW_SUPERUSER 1

COPY --from=composer:2.5.1 /usr/bin/composer /usr/bin/composer

# Install packages
RUN apk add --no-cache git

