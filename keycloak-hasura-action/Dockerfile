FROM node:14-alpine

WORKDIR /app

COPY ./* ./

RUN npm install
RUN npm ci

CMD node .
