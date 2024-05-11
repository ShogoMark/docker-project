FROM node:14.21.3

RUN mkdir -p /home/backend

COPY package*.json /home/backend/

RUN npm install

COPY ../server /home/backend/

EXPOSE 8080

CMD ["node", "index.mjs"]