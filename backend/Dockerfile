FROM node:12.14.0-alpine3.11

RUN apk add --no-cache bash

RUN touch /root/.bashrc | echo "PS1='\w\$ '" >> /root/.bashrc

WORKDIR /home/node/app
