# Base Image
FROM node:16-alpine

# Create app directory
WORKDIR /usr/src/app

# Install app dependencies
COPY package*.json ./
RUN npm install

# Bundle app source
COPY . .

# App runs on port 3000
EXPOSE 3000

# Command to run the app
CMD ["npm", "start"]
