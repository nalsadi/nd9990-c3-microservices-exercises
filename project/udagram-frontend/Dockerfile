FROM node:12.17.0

WORKDIR /usr/src/app

RUN npm install -g @ionic/cli

COPY . .

RUN npm ci

RUN ionic build

EXPOSE 8100

CMD ionic serve