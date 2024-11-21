FROM node:22

ENV AppPath=/app
RUN mkdir -p $AppPath
WORKDIR $AppPath

COPY package*.json $AppPath
RUN npm install

COPY index.js $AppPath