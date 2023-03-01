FROM nginx:1.23.3

COPY . /var/www/html


COPY docker/nginx/default.conf /etc/nginx/conf.d/default.conf

RUN  chown -R www-data:www-data /var/www