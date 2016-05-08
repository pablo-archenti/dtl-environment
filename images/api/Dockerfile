FROM node:4.3.2

RUN apt-get update && apt-get install -y mysql-client

RUN mkdir /app

RUN npm install supervisor -g

CMD ["npm start"]
