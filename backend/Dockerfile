FROM node:20.9.0-alpine

WORKDIR /app

COPY package*.json ./

COPY . .

RUN npm install --legacy-peer-deps

EXPOSE 8888

CMD ["npm", "run", "dev"]