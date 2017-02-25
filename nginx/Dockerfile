FROM tutum/nginx
RUN rm /etc/nginx/sites-enabled/default
ADD sites-enabled/ /etc/nginx/sites-enabled

# setup
COPY web-app /usr/src/web-app/
RUN chown -R www-data:www-data /usr/src/web-app/