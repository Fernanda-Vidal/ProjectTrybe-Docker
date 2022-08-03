FROM node:14
WORKDIR /backend

ADD node_modules.tar.gz .
COPY . .

EXPOSE 3001

ENTRYPOINT ["npm", "start"]
