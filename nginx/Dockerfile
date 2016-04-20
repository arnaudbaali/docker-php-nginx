FROM nginx

ADD conf/vhost.conf /etc/nginx/conf.d/default.conf
RUN echo "upstream php-upstream { server php:9000; }" > /etc/nginx/conf.d/upstream.conf
RUN usermod -u 1000 www-data

CMD nginx -g 'daemon off;'

EXPOSE 80
