FROM node:16-alpine
WORKDIR /server
COPY . /server/
RUN npm install
EXPOSE 5000
CMD [ "node", "./server.js" ]