# Simple Dockerfile to run my website in a container
# to run: docker run -d --name tomreeb-web -p 8080:80 
FROM nginx

WORKDIR /usr/share/nginx/

RUN git clone https://github.com/tomreeb/v5.git /usr/share/nginx/html

EXPOSE 80