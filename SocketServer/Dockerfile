FROM node:10

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY index.js ./

EXPOSE 5252

CMD [ "node", "index.js" ]
