FROM node:16

WORKDIR /usr/src/app
# referenced from:
# https://nodejs.org/en/docs/guides/nodejs-docker-webapp/
COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080
CMD [ "node", "index.js" ]
