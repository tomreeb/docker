# Simple Dockerfile to run my website in a container
# to run: docker run -d --name tomreeb-web -p 8080:80 
FROM tomreeb/nginx

MAINTAINER Tom Reeb <tom@reeb.me>

WORKDIR /usr/share/nginx/

RUN git clone https://github.com/tomreeb/v5.git /usr/share/nginx/html

EXPOSE 80