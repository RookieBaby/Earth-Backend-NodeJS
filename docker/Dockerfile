FROM node:8.9.0

RUN mkdir -p /usr/src/app
COPY package.json /usr/src/app/
RUN npm install
COPY . /usr/src/app

EXPOSE 3000

CMD npm run prod
