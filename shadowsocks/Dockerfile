# shadowsocks
#
# VERSION 1.0

FROM centos:7.6.1810
MAINTAINER GGBANDXYZ <ggbandxyz@gmail.com>

RUN yum -y install epel-release \
    && yum -y install python-pip \
    && yum clean all\
    && pip install --upgrade pip \
    && pip install shadowsocks==2.8.2 

# Configure container to run as an executable
ENTRYPOINT ["/usr/bin/ssserver","-c","/etc/shadowsocks.json"]