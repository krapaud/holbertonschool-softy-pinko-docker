FROM ubuntu:latest

WORKDIR /app

RUN apt-get update && \
    DEBIAN_FRONTEND=noninteractive apt-get upgrade -y && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y python3 python3-pip

RUN rm /usr/lib/python*/EXTERNALLY-MANAGED

RUN pip3 install flask flask-cors

COPY ./api.py /app/api.py

EXPOSE 5252

CMD ["python3", "api.py"]