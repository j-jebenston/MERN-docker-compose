FROM node:24-alpine3.21

WORKDIR /app

copy package*.json .

RUN npm install

COPY . .

EXPOSE 5173

CMD ["npm", "run", "dev"]