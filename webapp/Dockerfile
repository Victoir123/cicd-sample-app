FROM node:alpine

WORKDIR /app


RUN pwd && ls -la


COPY ./yarn.lock ./package.json ./

RUN yarn install

COPY . .

EXPOSE 3000

CMD ["yarn", "start"]
