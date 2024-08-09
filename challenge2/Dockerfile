# Use the official Node.js image from the Docker Hub
FROM node:14

# Create a directory to hold the application code inside the image
WORKDIR /usr/src/app

# Copy the application files
COPY package*.json ./

# Install dependencies
RUN npm install

COPY . .

# Expose port 3000
EXPOSE 3000

# Start the application
CMD ["node", "server.js"]
