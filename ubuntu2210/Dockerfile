FROM ubuntu:22.10
RUN apt update
ARG DEBIAN_FRONTEND=noninteractive
RUN apt install apache2
COPY index.html /var/www/html/index.html
ENTRYPOINT ["apachectl" , "-DFOREGROUND"]
