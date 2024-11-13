FROM ubuntu:22.04

RUN apt-get update
RUN apt-get install apache2 -y
RUN apt-get install mariadb-server -y
COPY . /var/www/html

EXPOSE 80

CMD ["apache2ctl","-D","FOREGROUND"]

