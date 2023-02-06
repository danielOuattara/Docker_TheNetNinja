# parent image 
FROM node:18.13-alpine3.16 
RUN npm i -g nodemon

WORKDIR /app

COPY package.json .
# install dependencies
RUN npm install
# source code
COPY . .



EXPOSE 4000
# required for docker desktop port mapping

CMD ["npm", "run", "dev"]

