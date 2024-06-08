FROM ubuntu:focal AS base
WORKDIR /usr/local/bin
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update && \
    apt-get upgrade -y && \
    apt-get install -y curl git build-essential sudo
WORKDIR /home/grantwforsythe
COPY . .
CMD ["sh"]

