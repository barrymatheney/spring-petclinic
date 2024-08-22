
FROM debian:stable-slim  AS build
RUN apt-get update
RUN apt-get install -y ca-certificates curl nodejs

RUN curl -fsSL https://get.docker.com -o get-docker.sh
RUN  sh ./get-docker.sh 


RUN docker buildx version
