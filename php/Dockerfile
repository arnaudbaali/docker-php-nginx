FROM php:5.6.20-fpm

#RUN apt-get update && apt-get install -y php5-intl php5-cgi php5-curl php5-gd php5-mysql php5-apcu php5-json php5-mcrypt

ADD symfony.pool.conf /etc/php5/fpm/pool.d/

RUN usermod -u 1000 www-data

EXPOSE 9000
