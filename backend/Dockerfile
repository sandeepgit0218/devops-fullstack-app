# Specify the base image
FROM node:14-alpine

# Set the working directory
WORKDIR /app

# Copy the entire backend directory to the container
COPY backend/ ./

# Expose the desired port (assuming the backend runs on port 8080)
EXPOSE 8080

# Start the backend application
CMD ["npm", "start"]
