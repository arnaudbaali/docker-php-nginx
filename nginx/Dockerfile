FROM nginx

MAINTAINER Arnaud Baali

# Add your vhost(s) file(s)
ADD conf/vhost.conf /etc/nginx/conf.d/default.conf

# Listen on the php container for FPM
RUN echo "upstream php-upstream { server php:9000; }" > /etc/nginx/conf.d/upstream.conf

# Add a user to www-data group
RUN usermod -u 1000 www-data

# Run nginx with no deamon
CMD nginx -g 'daemon off;'

# Expose port(s) of your container
EXPOSE 80
