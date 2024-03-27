FROM ubuntu:22.04

WORKDIR /usr/src/app

COPY script.sh .

RUN apt-get -y update

RUN apt-get -y install curl

CMD ./script.sh