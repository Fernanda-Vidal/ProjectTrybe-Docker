FROM node:14
WORKDIR /frontend

ADD node_modules.tar.gz /frontend/
COPY . .

EXPOSE 3000

ENTRYPOINT ["npm", "start"]
