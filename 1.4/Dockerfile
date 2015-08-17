FROM debian:wheezy
MAINTAINER Coaxial <coaxial@cxial.tk>
ENV DEBIAN_FRONTEND nonintaractive
RUN echo 'deb http://files.freeswitch.org/repo/deb/debian/ wheezy main' >> /etc/apt/sources.list.d/freeswitch.list &&\
    gpg --keyserver pool.sks-keyservers.net --recv-key D76EDC7725E010CF &&\
    gpg -a --export D76EDC7725E010CF | apt-key add - &&\
    apt-get update &&\
    apt-get upgrade -y -qq &&\
    apt-get install freeswitch -y -qq &&\
    apt-get install freeswitch-mod-commands -y -qq &&\
    apt-get install freeswitch-mod-console -y -qq &&\
    apt-get clean

ENTRYPOINT ["freeswitch"]
