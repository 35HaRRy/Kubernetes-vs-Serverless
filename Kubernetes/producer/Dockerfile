FROM node:carbon-alpin
CMD ["npm", "start"]
WORKDIR /app
EXPOSE 80
COPY package*.json ./
RUN npm install
COPY . .
