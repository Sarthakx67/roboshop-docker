FROM node:14
EXPOSE 8080
USER roboshop
WORKDIR /opt/server
COPY package.json .
COPY server.js .
RUN npm install
CMD [ "node" , "server.js" ]