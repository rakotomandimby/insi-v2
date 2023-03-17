FROM fedora:37
RUN dnf install -y httpd
RUN rm /etc/httpd/conf.d/welcome.conf
COPY ./index.html  /var/www/html/index.html
ENTRYPOINT ["/sbin/httpd", "-DFOREGROUND"]
