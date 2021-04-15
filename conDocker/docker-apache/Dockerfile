FROM ubuntu/apache2
RUN apt update
#RUN apt install apache2 -y
EXPOSE 8080

ADD index.html /var/www/html/index.html

CMD apachectl -D FOREGROUND

