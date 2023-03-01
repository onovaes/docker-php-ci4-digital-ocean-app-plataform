FROM php:8.1-fpm

# INTL EXTENSION REQUIRED FOR CODEIGNITER
RUN apt-get -y update \
&& apt-get install -y libicu-dev \
&& docker-php-ext-configure intl \
&& docker-php-ext-install intl
