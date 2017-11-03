FROM node:8.7

RUN mkdir -p /usr/src/pp
WORKDIR /usr/src/app

ARG NODE_ENV
ENV NODE_ENV $NODE_ENV
COPY . /usr/sc/app

RUN yarn global add webpack webpack-dev-server
RUN yarn install --no-bin-links
