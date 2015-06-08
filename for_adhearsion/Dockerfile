FROM coaxial/freeswitch:1.4.19
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
    apt-get install freeswitch-mod-shout -y -qq &&\
    apt-get install libvorbis0a libogg0 libogg-dev libvorbis-dev -y -qq &&\
    apt-get install freeswitch-mod-ssml -y -qq &&\
    apt-get clean

# mod_rayo
EXPOSE 5222
# SIP internal and external
EXPOSE 5060 5080
# RTP
EXPOSE 16384 16385 16386 16387 16388 16389 16390 16391 16392 16393 16394 16395 16396 16397 16398 16399 16400 16401 16402 16403 16404 16405 16406 16407 16408 16409 16410 16411 16412 16413 16414 16415 16416 16417 16418 16419 16420 16421 16422 16423 16424 16425 16426 16427 16428 16429 16430 16431 16432 16433 16434 16435 16436 16437 16438 16439 16440 16441 16442 16443 16444 16445 16446 16447 16448 16449 16450 16451 16452 16453 16454 16455 16456 16457 16458 16459 16460 16461 16462 16463 16464 16465 16466 16467 16468 16469 16470 16471 16472 16473 16474 16475 16476 16477 16478 16479 16480 16481 16482 16483 16484
