FROM ubuntu:xenial 
RUN apt-get install -y apt-transport-https curl software-properties-common python-software-properties
RUN curl -fsSL https://apt.dockerproject.org/gpg | apt-key add 
RUN echo 'deb https://apt.dockerproject.org/repo ubuntu-xenial main' > /etc/apt/sources.list.d/docker.list
RUN apt-get update
RUN apt-get install -y python3-pip
RUN apt-get install -y build-essential libssl-dev libffi-dev python-dev
