FROM ubuntu:20.04

ENV DEBIAN_FRONTEND noninteractive
RUN apt-get update && \
apt-get install
run apt-get install -y apache2 apache2-utils
EXPOSE 80
CMD [“apache2ctl”, “-D”, “FOREGROUND”]

