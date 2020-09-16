# Specify a base image
FROM node:12.13.0-alpine

WORKDIR /app

# Install dependencies
COPY package.json .
RUN npm install
COPY . .

EXPOSE 9000

CMD [ "npm", "run", "dev" ]
