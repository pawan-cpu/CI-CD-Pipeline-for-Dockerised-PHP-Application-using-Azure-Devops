FROM httpd:2.4-alpine
RUN apk update; \
    apk upgrade;
COPY app.conf /usr/local/apache2/conf/app.conf
RUN echo "Include /usr/local/apache2/conf/app.conf" \
    >> /usr/local/apache2/conf/httpd.conf
#RUN chown -R www-data:www-data /var/www/app
