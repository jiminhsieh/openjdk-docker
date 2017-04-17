FROM ubuntu:16.04

ENV LANG C.UTF-8
ENV JAVA_VERSION 8u121
ENV JAVA_UBUNTU_VERSION ${JAVA_VERSION}-b13-0ubuntu1.16.04.2

RUN apt-get update && \
	apt-get install -y openjdk-8-jdk=${JAVA_UBUNTU_VERSION} \
	openjdk-8-jdk-headless=${JAVA_UBUNTU_VERSION} && \
	rm -rf /var/lib/apt/lists/*
