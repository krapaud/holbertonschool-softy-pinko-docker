FROM ubuntu:latest

RUN apt-get update && \
    DEBIAN_FRONTEND=noninteractive apt-get upgrade -y && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y python3 python3-pip && \
    pip3 install flask && flask-cors

WORKDIR /app

COPY ./api.py /app/api.py

CMD ["python3", "api.py"]
