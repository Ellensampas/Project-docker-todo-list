FROM node:14-alpine

WORKDIR /dockerbackend

ADD node_modules.tar.gz .

COPY . .

EXPOSE 3001

CMD [ "npm", "start" ]