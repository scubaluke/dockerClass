FROM node:alpine


WORKDIR /usr/app
COPY ./package.json ./

RUN npm install

copy ./ ./

CMD ["npm", "start"]