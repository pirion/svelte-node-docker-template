FROM node:latest

WORKDIR /usr/src/app

ENV NODE_ENV=development
ENV PORT=3000
ENV HOST=0.0.0.0

COPY package.json ./

RUN npm install --production=false

COPY . .

EXPOSE ${NODE_PORT}