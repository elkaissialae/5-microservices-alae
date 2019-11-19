FROM ubuntu:latest
RUN apt-get install -y nginx
RUN apt-get update
VOLUME /var/www/html/
ENTRYPOINT ["nginx", "-g", "daemon off;"]
