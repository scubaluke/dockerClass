# specify base image
FROM node:19-alpine

WORKDIR /usr/app
COPY ./package.json ./
# install dependencys 
RUN npm install
copy ./ ./

#default command
CMD ["npm", "start"]