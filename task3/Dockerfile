FROM node:16-alpine

WORKDIR /home/ilovedocker/app

COPY ./packages/package*.json ./

RUN npm ci

COPY ./src ./

ENTRYPOINT ["node", "main.js"]
