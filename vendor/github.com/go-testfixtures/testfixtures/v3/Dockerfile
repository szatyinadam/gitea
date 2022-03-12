FROM golang:1.16.13-alpine

RUN apk update
RUN apk add alpine-sdk

WORKDIR /testfixtures
COPY . .

RUN go mod download
