FROM node:16

# Create app directory
WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

# If you are building your code for production
# RUN npm ci --only-production

COPY . .

EXPOSE 2000

CMD [ "node", "index.js" ]