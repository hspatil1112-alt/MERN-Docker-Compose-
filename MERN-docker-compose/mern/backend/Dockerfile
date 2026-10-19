FROM node:18.9.1

WORKDIR /app

COPY  . .

COPY package.jason .

RUN  npm install

EXPOSE 5050

CMD ["npm","start"]