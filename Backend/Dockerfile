# Use Node base image
FROM node:18

# Create app directory
WORKDIR /usr/src/app

# Install app dependencies
COPY package*.json ./
RUN npm install

# Bundle app source
COPY . .

# Expose backend port
EXPOSE 3021

# Run the backend
CMD ["node", "server.js"]

