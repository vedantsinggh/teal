FROM node:18-slim

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

WORKDIR /app

EXPOSE 5173

CMD ["npm", "run", "dev"]
