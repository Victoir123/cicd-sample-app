FROM node:alpine

WORKDIR /app

COPY ./webapp/package.json ./webapp/yarn.lock ./

RUN yarn install

COPY . .

EXPOSE 3000

CMD ["yarn", "start"]
