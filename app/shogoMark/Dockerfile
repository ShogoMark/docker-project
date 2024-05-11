FROM node

RUN mkdir -p /home/app

COPY ../app/package*.json /home/app

RUN npm install

COPY ../app /home/app

RUN npm run build

EXPOSE 3000

CMD ["npm", "start"]