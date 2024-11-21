FROM node:22

WORKDIR $AppPath

COPY package*.json ./
RUN npm install

COPY . .

RUN npm run build