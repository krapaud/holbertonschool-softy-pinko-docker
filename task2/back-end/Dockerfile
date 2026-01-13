FROM ubuntu:latest

RUN apt-get update && \
    DEBIAN_FRONTEND=noninteractive apt-get upgrade -y && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y python3 python3-pip && \
    pip3 install flask

COPY ./api.py /app/api.py

EXPOSE 5252

CMD ["echo", "Hello, World!"]