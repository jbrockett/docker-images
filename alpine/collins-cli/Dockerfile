FROM alpine:3.8

MAINTAINER Jeremy Brockett

RUN apk add --no-cache ruby ruby-json ruby-io-console ruby-bigdecimal ruby-etc && \
    gem install --no-rdoc --no-ri collins-cli

ENTRYPOINT ["collins"]
CMD ["-h"]
