# Start with Node.js 10
FROM node:10

# Image directory where commands run
WORKDIR /usr/src/app

# Copy package files and install dependencies
COPY ./app/package*.json ./
RUN npm install express

# Copy app files into image
COPY ./app/. .

# Command to run when container starts
CMD ["npm", "start"]