
# Use an official Node.js runtime as a base image
FROM node:14

# Set the working directory to /app
WORKDIR /app

# Copy package.json and package-lock.json to the working directory
COPY package*.json ./

# Install app dependencies
RUN npm install

# Install http-server globally
RUN npm install -g http-server

# Copy all files to the working directory
COPY . .

# Expose the port that the app will run on
EXPOSE 8080

# Define the command to run your app
CMD ["npm", "start"]

