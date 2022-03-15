FROM node:14

WORKDIR /image
COPY package.json .
RUN npm install
COPY . .
CMD npm start
