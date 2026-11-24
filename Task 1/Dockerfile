FROM ubuntu:24.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && \
apt-get install -y apache2 && \
apt-get clean

CMD ["apachectl", "-D", "FOREGROUND"]