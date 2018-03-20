FROM alpine:latest
LABEL maintainer "Taisuke Miyazaki <imishinist@gmail.com>"

RUN apk update
RUN apk add bind-tools netcat-openbsd iputils tcpdump curl
RUN apk upgrade

ENTRYPOINT ["/bin/sh", "-c", "while true; do sleep 1; done"]
