FROM jbrockett/alpine:3.4
MAINTAINER Jeremy Brockett

RUN echo http://dl-cdn.alpinelinux.org/alpine/edge/community >> /etc/apk/repositories && \
    apk --no-cache add apache2 php7-apache2 php7 && \
    mkdir -p /run/apache2

COPY root /
COPY apache.conf /etc/apache2/conf.d/docker.conf

EXPOSE 80
