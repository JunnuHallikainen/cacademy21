FROM node:16-alpine

WORKDIR /usr/src/app

COPY package.json package-lock.json /usr/src/app/

RUN npm install

COPY . /usr/src/app/

CMD [ "node", "index.js" ]