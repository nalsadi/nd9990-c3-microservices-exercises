FROM node:12.17.0

WORKDIR /usr/src/app

COPY . .

RUN npm ci

EXPOSE 8090

CMD npm run prod