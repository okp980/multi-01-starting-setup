FROM node:14-alpine

WORKDIR /app

COPY package.json .

RUN npm install

ENV MONGO_USERNAME=root
ENV MONGO_PASSWORD=example

COPY . .

CMD ["node", "app.js"]