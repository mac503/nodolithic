FROM node:14.5-alpine

RUN apk update && apk upgrade

RUN apk add bash
RUN apk add zsh
RUN apk add nano

USER node

WORKDIR /app

CMD [ "node", "api/app.js" ]