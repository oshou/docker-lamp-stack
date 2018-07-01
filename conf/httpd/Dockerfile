FROM php:7.2-apache-stretch
ENV TZ JST-9
RUN echo "install mysql mysqli pdo driver" \
    && docker-php-ext-install mysqli pdo pdo_mysql
