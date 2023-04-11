FROM php:8.0-apache
WORKDIR /var/www/html


RUN apt-get update
RUN a2enmod rewrite

RUN service apache2 restart

COPY www/ .
EXPOSE 80