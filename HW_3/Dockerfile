FROM node:18-slim

WORKDIR /app

COPY package.json .
COPY app.js .

RUN npm install --only=production

CMD ["npm", "start"]
