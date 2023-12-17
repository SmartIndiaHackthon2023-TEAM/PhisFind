FROM node:14

WORKDIR /app/frontend/client

COPY ./package.json .
COPY ./package-lock.json .
RUN npm install --force

COPY . .

EXPOSE 5173

CMD ["npm","run","dev"]