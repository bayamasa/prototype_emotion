FROM golang:1.16.0-alpine3.13

WORKDIR /app

ENV GO111MODULE=on

RUN apk add --no-cache \
        alpine-sdk \
        git \
    && go get github.com/pilu/fresh

EXPOSE 8080

CMD ["fresh"]
