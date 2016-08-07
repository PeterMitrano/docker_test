FROM python:2.7.10
MAINTAINER Peter Mitrano <mitranopeter@gmail.com>

RUN apt-get update \
    && apt-get install -y vim \
    && apt-get install -y tmux

RUN pip install boto3

WORKDIR /root/src
