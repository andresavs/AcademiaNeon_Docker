FROM node:10-slim

LABEL maintainer="Andresa <andresa.vs@gmail.com>"

WORKDIR /usr/app/hello
COPY /app/app_node1 .

RUN npm install 

EXPOSE 3000

ENTRYPOINT ["node", "app.js"]