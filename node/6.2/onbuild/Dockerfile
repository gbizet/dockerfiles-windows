FROM node:6.2.1

RUN mkdir \app
WORKDIR /app

ONBUILD COPY package.json package.json
ONBUILD RUN npm install
ONBUILD COPY . .

CMD [ "npm.cmd", "start" ]
