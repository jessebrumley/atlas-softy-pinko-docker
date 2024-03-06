FROM ubuntu:latest

LABEL maintainer="Jesse Brumley"

COPY . /app

WORKDIR /app

RUN apt-get update && apt-get upgrade -y

ENTRYPOINT ["echo", "Hello, World!"]