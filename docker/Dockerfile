FROM ubuntu:latest

RUN apt update && apt install curl -y
RUN curl -L http://download.processing.org/processing-3.4-linux64.tgz -o processing.tgz
RUN tar -zxvf processing.tgz \
        && rm processing.tgz
        && mv processing-3.4 /usr/local \
        && ln -s /usr/local/processing-3.4/process /usr/local/bin
        && ln -s /usr/local/processing-3.4/process-java /usr/local/bin
