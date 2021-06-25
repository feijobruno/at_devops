FROM node:12-slim
WORKDIR /home/node/app
COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 3001

CMD ["npm", "start"]