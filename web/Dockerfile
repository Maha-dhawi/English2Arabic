FROM node:10-alpine

WORKDIR /var/www

COPY . .

RUN npm install

VOLUME [ "/var/www" ]

EXPOSE 3000

CMD [ "node", "index.js" ]