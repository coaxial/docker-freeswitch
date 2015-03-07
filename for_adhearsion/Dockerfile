FROM coaxial/freeswitch:1.4
MAINTAINER Coaxial <py@poujade.org>
ENV DEBIAN_FRONTEND noninteractive
RUN apt-get install freeswitch-mod-dialplan-xml -y -qq &&\
    apt-get install freeswitch-mod-dptools -y -qq &&\
    apt-get install freeswitch-mod-event-socket -y -qq &&\
    apt-get install freeswitch-mod-flite -y -qq &&\
    apt-get install freeswitch-mod-logfile -y -qq &&\
    apt-get install freeswitch-mod-loopback -y -qq &&\
    apt-get install freeswitch-mod-native-file -y -qq &&\
    apt-get install freeswitch-mod-rayo -y -qq &&\
    apt-get install freeswitch-mod-sndfile -y -qq &&\
    apt-get install freeswitch-mod-sofia -y -qq &&\
    apt-get install freeswitch-mod-ssml -y -qq &&\
    apt-get clean

