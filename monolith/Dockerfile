FROM node:25.6.0-bookworm

COPY . /app

WORKDIR /app

RUN npm install --only=production

EXPOSE 3000

CMD [ "node", "./server.js"]
