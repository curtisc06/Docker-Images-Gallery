FROM node:15.14-alpine

WORKDIR /app

EXPOSE 3000

COPY package.json package-lock.json ./

COPY . ./

CMD ["npm","start"]