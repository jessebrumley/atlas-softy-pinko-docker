FROM ubuntu:latest

LABEL maintainer="Jesse Brumley"

RUN apt-get update && apt-get upgrade -y && \
    apt-get install -y python3 python3-pip && \
    pip3 install flask flask-cors

COPY api.py /app/api.py

WORKDIR /app

EXPOSE 5252

ENTRYPOINT ["python3", "api.py"]