FROM continuumio/miniconda3:latest
LABEL maintainer="a.kuederle@gmail.com"

# Install openjdk8
RUN echo "deb http://http.debian.net/debian jessie-backports main" > /etc/apt/sources.list.d/jessie-backports.list \
    && apt-get update --fix-missing \
    && apt-get install -y -t jessie-backports openjdk-8-jdk
ENV JAVA_HOME /usr/lib/jvm/java-8-openjdk-amd64
