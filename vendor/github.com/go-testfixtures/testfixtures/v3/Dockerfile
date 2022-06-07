FROM golang:1.18.0-alpine

RUN apk update
RUN apk add alpine-sdk

WORKDIR /testfixtures
COPY . .

RUN go mod download
