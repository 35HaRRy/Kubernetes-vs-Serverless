FROM node:carbon-alpin
CMD ['npm', 'start']
WORKINDIR /app
EXPOSE 80
COPY package*.json ./
RUN npm install
COPY . .
