FROM ubuntu:16.04

RUN apt-get update && apt-get install -y python-software-properties software-properties-common
RUN apt-get install -y iputils-ping
RUN add-apt-repository ppa:webupd8team/java
RUN apt-get install -y vim
RUN echo "oracle-java8-installer shared/accepted-oracle-license-v1-1 boolean true" | debconf-set-selections

RUN apt-get update && apt-get install -y oracle-java8-installer