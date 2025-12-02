# syntax=docker/dockerfile:1

FROM --platform=linux/amd64 node:21.5.0
WORKDIR /app
COPY package.json yarn.lock ./
RUN yarn install
COPY . .
CMD [ "node", "server.js" ]
