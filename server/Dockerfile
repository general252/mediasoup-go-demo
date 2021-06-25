FROM ubuntu:20.04

ADD ./public /home/public
ADD ./certs /home/certs
ADD ./mediasoup-worker /home/mediasoup-worker
ADD ./server /home/server

WORKDIR /home

CMD [ "/home/server" ]
