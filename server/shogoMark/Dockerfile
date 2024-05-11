FROM node

RUN mkdir -p /home/app

COPY ../server/package*.json /home/backend

RUN npm install

COPY ../server /home/backend

EXPOSE 8080

CMD ["node", "index.mjs"]