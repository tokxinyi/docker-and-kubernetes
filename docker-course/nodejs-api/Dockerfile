# FROM node:latest
# will reduce the image size
FROM node:alpine

# use /app as the working directory if it exists, otherwise create this folder in the container
WORKDIR /app

# add all the files in current local directory into the /app directory
ADD . .

# install all the dependencies in package.json
RUN npm install

# start the api
CMD node app.js