# Specify a base image
FROM node:alpine

# Set the default workdir inside the container's filesystem
WORKDIR /usr/app

# Install some dependencies
COPY package.json .
RUN npm install

# Copy the rest of the project files
COPY . .

# Default command
CMD ["npm", "start"]
