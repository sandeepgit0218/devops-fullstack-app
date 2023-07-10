# Specify the base image
FROM node:14-alpine

# Set the working directory
WORKDIR /app

# Copy the package.json and package-lock.json files
COPY frontend/package*.json ./

# Install the dependencies
RUN npm install

# Copy the rest of the application code
COPY frontend/ ./

RUN npm run build

EXPOSE 3000

# Start the frontend application
CMD ["npm", "start"]
