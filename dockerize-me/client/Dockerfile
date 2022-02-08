FROM node:14.18

# MAINTAINER Abel-Archila

WORKDIR /app

COPY /public/index.html  public/index.html
COPY /src/index.js  src/index.js 

COPY package.json ./package.json

RUN npm install
COPY . .
EXPOSE 3000
CMD ["npm", "start"]