FROM ubuntu:latest

LABEL maintainer="Jesse Brumley"

COPY . /app

WORKDIR /app

RUN apt-get update

RUN apt-get upgrade -y

ENTRYPOINT ["echo", “Hello, World!”]