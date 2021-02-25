FROM node:12.17.0

WORKDIR /usr/src/app

COPY . .

RUN npm ci

EXPOSE 8080

CMD npm run dev