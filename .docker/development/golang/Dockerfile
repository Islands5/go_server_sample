FROM golang:1.10.3-alpine

ENV LANG=C.UTF-8 \
    TZ=Asia/Tokyo \
    APP_HOME=/go/src/api

RUN apk update \
 && apk add --no-cache git \
 && go get -u github.com/golang/dep/cmd/dep

WORKDIR ${APP_HOME}
