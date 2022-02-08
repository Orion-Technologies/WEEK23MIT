FROM node:slim

# MAINTAINER  abel.archila@gmail.com

WORKDIR /app

COPY package.json ./package.json

RUN npm install
COPY . .
EXPOSE 8080
CMD ["npm", "start"]
