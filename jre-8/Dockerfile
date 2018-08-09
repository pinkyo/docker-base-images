FROM centos:7

RUN mkdir -p /opt/nemo/
COPY ./jre1.8.0_172 /opt/nemo/jre-8u172
RUN chmod +x /opt/nemo/jre-8u172/bin/*

ENV JAVA_HOME /opt/nemo/jre-8u172

LABEL maintainer="yinkainian"
LABEL email="yinkn@outlook.com"
LABEL version="1.0"