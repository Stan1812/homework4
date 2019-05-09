FROM node:10.10
COPY . /app
WORKDIR /app
RUN npm install --registry=https://registry.npm.taobao.org
CMD node sender.js