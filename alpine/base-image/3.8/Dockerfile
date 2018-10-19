FROM alpine:3.8
MAINTAINER Jeremy Brockett

RUN apk --no-cache add dumb-init

ENTRYPOINT ["/usr/bin/dumb-init", "--"]
