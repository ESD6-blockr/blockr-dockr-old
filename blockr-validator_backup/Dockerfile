FROM node:8
WORKDIR /app
COPY package.json ./package.json
COPY package-lock.json ./package-lock.json
RUN npm i

COPY lib ./lib
COPY logic ./logic
COPY public ./public
COPY services ./services
COPY tasks ./tasks
COPY util ./util
COPY validator-mongodb ./validator-mongodb

COPY .env ./.env
COPY server.js ./server.js

ENTRYPOINT ["node", "server.js"]