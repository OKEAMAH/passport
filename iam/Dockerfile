FROM node:20.15.1
WORKDIR /usr/src

COPY . .

RUN yarn

EXPOSE 80 443
CMD [ "node", "iam/dist/iam/src/main.js" ]
