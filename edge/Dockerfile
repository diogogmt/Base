FROM alpine:edge

RUN apk add --no-cache tini

ENTRYPOINT ["/sbin/tini", "--"]
