FROM node:14.21.3

RUN mkdir -p /home/app/

COPY package*.json /home/app/

RUN npm install

COPY /app /home/app/

RUN npm run build

EXPOSE 3000

CMD ["npm", "start"]
