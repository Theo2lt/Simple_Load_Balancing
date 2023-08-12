# SPECIFIE LA DISTRIBUTION
FROM debian:buster

RUN apt-get update

# UDPATE & INSTALLATION
RUN apt-get install -y nginx

COPY default.conf   /etc/nginx/sites-available/default

ENTRYPOINT ["nginx", "-g", "daemon off;"]