FROM php:5.6.20-fpm

MAINTAINER Arnaud Baali

# Install specific packages for your project
RUN apt-get update && apt-get install -y php5-intl php5-cgi php5-curl php5-gd php5-mysql php5-apcu php5-json php5-mcrypt

# Define a specific config for your PHP-FPM
ADD symfony.pool.conf /etc/php5/fpm/pool.d/

# Add the active user as a member of the group www-data
RUN usermod -u 1000 www-data

# Expose a port for your PHP-FPM
EXPOSE 9000
