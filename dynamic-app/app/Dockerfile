# Use the official Node.js image from the Docker Hub
FROM node:14

# Create and change to the app directory
WORKDIR /usr/src/app

# Copy application files
COPY package*.json ./
COPY server.js ./

# Install dependencies
RUN npm install

# Expose port 3000
EXPOSE 3000

# Command to run the application
CMD ["npm", "start"]
