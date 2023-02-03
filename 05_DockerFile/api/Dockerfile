# parent image 
FROM node:18.13-alpine3.16 

WORKDIR /server

# source code
COPY . .

# install dependencies
RUN npm install

# required for docker desktop port mapping
EXPOSE 4000


# on runtime
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