FROM php:8.1-fpm-alpine

# Copy all the php files in order for the php to proccess

COPY ./app .

RUN docker-php-ext-install pdo pdo_mysql