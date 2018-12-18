FROM alpine:3.8
MAINTAINER Jeremy Brockett

RUN apk --no-cache add tini

ENTRYPOINT ["/sbin/tini", "--"]
