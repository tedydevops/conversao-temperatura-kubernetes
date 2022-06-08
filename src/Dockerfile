FROM node:16.15.0
#idempotência: definindo versão da imagem
WORKDIR /app
COPY ./package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
