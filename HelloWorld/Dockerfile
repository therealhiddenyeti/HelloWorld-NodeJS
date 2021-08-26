FROM node:16
WORKDIR /Users/thomasgould/Documents/NodeJS/HelloWorld/app/build
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "npm", "start" ]
