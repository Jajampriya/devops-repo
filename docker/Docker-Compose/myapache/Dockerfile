FROM ubuntu:latest
MAINTAINER Priyajajam <priyajajam@gmail.com>
RUN apt-get update
RUN apt-get install apache2 -y
RUN echo "Welcome to the world of docker images" > /var/www/html/index.html
COPY priya.html /var/www/html/info.html
EXPOSE 80
CMD ["/usr/sbin/apache2ctl", "-D","FOREGROUND"]

