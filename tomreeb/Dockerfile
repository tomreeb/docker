# Simple Dockerfile to run my website in a container
# to run: docker run -d --name tomreeb-web -p 8080:80
FROM richarvey/nginx-php-fpm:latest

MAINTAINER Tom Reeb <tom@reeb.me>

RUN apt-get update && apt-get install git -y
RUN rm -rf /usr/share/nginx/html
RUN git clone https://github.com/tomreeb/v5.git /usr/share/nginx/html

EXPOSE 80
