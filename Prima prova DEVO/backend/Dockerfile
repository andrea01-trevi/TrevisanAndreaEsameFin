FROM node:14

WORKDIR /backend

COPY package.json .

RUN npm install
#RUN npm i pg
#RUN npm i express
#RUN npm i body-parser
#RUN npm i querystring



COPY . .

CMD ["node", "backendApp.js"]