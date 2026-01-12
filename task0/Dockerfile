FROM ubuntu:latest

WORKDIR /app

RUN apt-get update && \
    DEBIAN_FRONTEND=noninteractive apt-get upgrade -y && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y python3 python3-pip && \
    pip3 install flask

CMD ["python3", "api.py"]