FROM node:boron

RUN mkdir -p /parse-server

WORKDIR /parse-server

COPY package.json /parse-server
RUN npm install 

COPY . /parse-server

EXPOSE 1337

CMD ["npm","start"]