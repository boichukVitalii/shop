FROM node:16-alpine
WORKDIR /client
COPY . /client/
RUN npm install
RUN npm run build
EXPOSE 3000
CMD [ "npm", "start" ]