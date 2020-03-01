# Specify a base image
FROM node:alpine

WORKDIR /usr/app

# Install some dependencies
# copy everything from current working directory (in hard-drive) to current working directory of the container
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]