FROM node:16

WORKDIR /user/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8070

CMD [ "node", "server.js" ]
