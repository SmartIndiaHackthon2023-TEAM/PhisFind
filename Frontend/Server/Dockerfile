FROM node:latest

ENV NODE_ENV=production

WORKDIR /app/frontend/api

COPY ./package.json .
COPY ./package-lock.json .
RUN npm install

COPY . .

EXPOSE 3000

CMD ["node", "API.js"]