FROM alpine:latest
RUN apk add --update nodejs nodejs-npm

WORKDIR /usr/src/
COPY ./app ./app
COPY ./package.json .

RUN npm i
EXPOSE 3000
CMD npm start
