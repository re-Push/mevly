FROM php:8.0-apache
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
RUN apt-get update && apt-get upgrade -y
RUN pwd
RUN ls -la
COPY gnuboard/ /var/www/html/.
