FROM node:14

USER root

WORKDIR /usr/src/ui

COPY ./package*.json ./

RUN npm install -g @vue/cli
RUN npm install
