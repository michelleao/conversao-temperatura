FROM node:18.11.0
WORKDIR /app
COPY package*.json ./
# npm antes para não ter que instalar toda vez antes de copiar tudo
RUN npm install
COPY . . 
EXPOSE 8080 
CMD ["node", "server.js"] 