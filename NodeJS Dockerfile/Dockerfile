# Dhaffa Agusrian Putra
# 11201020

FROM node:14

COPY package.json /usr/src/app/
COPY package-lock.json /usr/src/app/

WORKDIR /usr/src/app
RUN npm install

COPY . /usr/src/app/

EXPOSE 3000