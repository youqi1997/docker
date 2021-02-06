FROM ubuntu:18.04
LABEL key="youqi"   

RUN echo "hello"
RUN apt-get update && apt-get install -y nginx
RUN echo "\ndaemon off;" >> /etc/nginx/nginx.conf
RUN chown -R www-data:www-data /var/lib/nginx