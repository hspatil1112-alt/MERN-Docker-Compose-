FROM node:18.9.1

WORKDIR /app

COPY package.jason .

COPY  . .

RUN  npm install

EXPOSE 5050

CMD ["npm","start"]