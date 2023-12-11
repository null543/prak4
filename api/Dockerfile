FROM node:alpine

WORKDIR /nodejs/timeapp

COPY package*.json ./

RUN npm install

COPY  . .

EXPOSE 4444

CMD ["npm", "run", "dev"]