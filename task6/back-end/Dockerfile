FROM ubuntu:latest

RUN apt-get update && apt-get upgrade -y

COPY ./api.py /app/api.py

EXPOSE 5252

CMD ["echo", "Hello, World!"]