FROM node:lts-alpine3.19

WORKDIR /app

COPY package*.json /app/

RUN npm install

COPY ./ /app/

CMD npm run build