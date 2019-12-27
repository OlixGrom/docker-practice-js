FROM node:12-alpine

WORKDIR ./home/node/app

RUN npm install

EXPOSE 8080

ENTRYPOINT ["npm", "install"]

CMD ["node", "server.js"]
