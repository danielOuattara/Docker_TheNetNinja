# parent image 
FROM node:18.13-alpine3.16 

WORKDIR /app

COPY package.json .
# install dependencies
RUN npm install
# source code
COPY . .



EXPOSE 4000
# required for docker desktop port mapping

CMD ["node", "app.js"]

# to build the image (in the same image as the Dockerfile )
# docker build

# Run from a terminal
# 1- find the image id/name, in CMD : "docker images" (from anywhere)
#
#
#
#
#
#
#