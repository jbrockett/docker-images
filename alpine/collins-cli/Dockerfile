FROM alpine:3.5

MAINTAINER Jeremy Brockett

RUN apk add --no-cache ruby-json && \
    gem install --no-rdoc --no-ri collins-cli

ENTRYPOINT ["collins"]
CMD ["-h"]
