FROM alpine:3.7

MAINTAINER Jeremy Brockett

RUN apk add --no-cache ruby-json ruby-io-console && \
    gem install --no-rdoc --no-ri collins-cli

ENTRYPOINT ["collins"]
CMD ["-h"]
