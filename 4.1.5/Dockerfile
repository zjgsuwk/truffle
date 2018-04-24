FROM node:7.4-alpine

RUN mkdir -p /data/webapps/
WORKDIR /data/webapps

RUN apk add -t .gyp --no-cache git python g++ make \
    && npm install -g truffle@4.1.x \
    && apk del .gyp
