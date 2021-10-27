FROM ubuntu:18.04
RUN apt-get update
RUN apt-get install -y curl
WORKDIR /usr/src/app
COPY script.sh .
CMD ./script.sh