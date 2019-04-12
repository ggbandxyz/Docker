# shadowsocks
#
# VERSION 1.0

#FROM centos:7.6.1810
#MAINTAINER GGBANDXYZ <ggbandxyz@gmail.com>

#RUN yum install python-setuptools \
#    && yum install easy_install pip \
#    && pip install shadowsocks==2.8.2

# Configure container to run as an executable
#ENTRYPOINT ["/usr/local/bin/ssserver"]

FROM alpine:3.9

MAINTAINER GGBANDXYZ <ggbandxyz@gmail.com>

RUN apk upgrade \
    && apk add --update \
    bash \
    python \
    python-dev \
    py-pip \
    mysql-dev \
    build-base \
  && pip install Flask \ 