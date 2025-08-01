FROM node:18

WORKDIR /virtual-assistant-backend

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8000

CMD ["npm", "start"]
