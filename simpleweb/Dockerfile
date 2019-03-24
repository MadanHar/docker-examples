# specify a base image
FROM node:alpine

# add the working directory reference
WORKDIR /usr/app

# copy the current working directory into the docker container
COPY ./package.json ./

# install some dependencies
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]
