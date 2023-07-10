FROM node:16-alpine

WORKDIR /home/ilovedocker/app

COPY /packages/package*.json ./

RUN npm i --omit=dev

COPY /src/ ./

EXPOSE 3000

ENTRYPOINT [ "node", "main.js" ]