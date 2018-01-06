FROM ubuntu:16.04

#MAINTAINER Advantech

# update and install libs
RUN apt-get update && \
    apt-get install -y git-core sudo net-tools iputils-ping libssl-dev gawk sed libxml2 libmosquitto1 sqlite3 && \
    useradd -m -k /home/adv adv -p adv -s /bin/bash -G sudo && \
    echo "adv ALL=(ALL) NOPASSWD: ALL" >> /etc/sudoers

WORKDIR /home/adv
