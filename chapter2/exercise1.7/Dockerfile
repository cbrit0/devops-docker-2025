FROM ubuntu:latest

RUN apt-get update && apt-get install -y curl

WORKDIR /usr/src/app

COPY script.sh .

RUN chmod +x script.sh

CMD ./script.sh
