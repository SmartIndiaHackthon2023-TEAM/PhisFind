FROM node:14

WORKDIR /app/frontend/api

COPY ./package.json .
COPY ./package-lock.json .
RUN npm install --force

COPY . .

EXPOSE 3000

CMD ["node", "API.js"]