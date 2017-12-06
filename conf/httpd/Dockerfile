FROM php:5.6-apache-jessie
ENV TZ JST-9
RUN echo "install mysql mysqli pdo driver" \
    && docker-php-ext-install mysqli pdo pdo_mysql
