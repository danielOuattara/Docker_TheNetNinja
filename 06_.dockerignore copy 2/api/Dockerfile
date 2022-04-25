# parent image 
FROM node:17-alpine 

WORKDIR /app

# source code
COPY . .

# install dependencies
RUN npm install

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