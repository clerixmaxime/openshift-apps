FROM node:8

WORKDIR /usr/src/app

ARG NODE_ENV
ENV NODE_ENV $NODE_ENV
COPY package.json /usr/src/app/
RUN npm install
COPY . /usr/src/app

CMD [ "npm", "start" ]

# replace this with your application's default port
EXPOSE 8080