FROM node:18.12.1
WORKDIR /app
COPY package*.json ./
RUN npm install
copy . .
EXPOSE 8080
CMD ["node", "server.js"]