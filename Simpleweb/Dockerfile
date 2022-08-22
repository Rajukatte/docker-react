# Specify a base image
FROM node:18-alpine

# Install some depenendencies
WORKDIR /opt/Simpleweb
COPY ./ /opt/Simpleweb
RUN npm install

# Default command
CMD ["npm", "start"]