FROM node:20-alpine 

COPY . /app
WORKDIR /app 
RUN npm ci 
CMD [ "node", "server.js" ]