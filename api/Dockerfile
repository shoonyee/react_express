# Specify a base image
FROM node:14

WORKDIR /app

# Install dependencies
COPY package.json .
RUN npm install
COPY . .

EXPOSE 9000

CMD [ "npm", "run", "dev" ]
