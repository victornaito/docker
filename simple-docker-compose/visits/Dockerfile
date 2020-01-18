FROM node:alpine

WORKDIR '/projects/visits'

COPY package.json .
RUN npm install
COPY . .

CMD [ "npm", "start" ]