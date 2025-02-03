# Use a Node.js base image
FROM node:18

# Set working directory
WORKDIR /app

# Copy project files
COPY . .

# Install dependencies and build
RUN npm install && npm run build

# Expose port
EXPOSE 3000

# Run the application
CMD ["npm", "start"]