FROM jbrockett/alpine:3.4
MAINTAINER Jeremy Brockett

RUN apk --no-cache add apache2 php5-apache2 php5-cli && \
    mkdir -p /run/apache2

COPY root /
COPY apache.conf /etc/apache2/conf.d/docker.conf

EXPOSE 80
