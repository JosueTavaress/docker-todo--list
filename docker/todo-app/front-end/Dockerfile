FROM node:14.4-alpine3.11

EXPOSE 3000

WORKDIR /

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT ["npm", "start"]

