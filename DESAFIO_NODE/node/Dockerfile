FROM node:16

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install -y && npm install mysql

COPY . .

EXPOSE 3000

#ENTRYPOINT [ "npm start" ]

CMD ["node","index.js"]