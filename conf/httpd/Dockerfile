FROM php:7.2.9-apache-stretch
RUN echo "install mysql mysqli pdo driver" \
    && docker-php-ext-install pdo_mysql mysqli msbstring
