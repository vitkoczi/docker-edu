# spec base image
FROM node:alpine

WORKDIR /usr/app

COPY ./package.json ./

RUN npm i

#dopy the necessary file
COPY ./ ./

#default command
CMD ["npm", "start"]
