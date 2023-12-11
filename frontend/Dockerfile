FROM node:alpine

WORKDIR /nodejs/timeapp

COPY package*.json ./

RUN npm install

COPY  . .

EXPOSE 8954

CMD ["npm", "run", "dev"]