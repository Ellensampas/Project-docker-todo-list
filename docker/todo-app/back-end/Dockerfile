FROM node:14 AS todobackend

WORKDIR /dockerbackend

ADD node_modules.tar.gz .

COPY . .

EXPOSE 3001

CMD [ "npm", "start" ]