FROM node:17.1-alpine

WORKDIR /app

EXPOSE 3000

COPY package.json package-lock.json ./

RUN npm install --silent 

COPY . ./

CMD [ "npm", "start" ]