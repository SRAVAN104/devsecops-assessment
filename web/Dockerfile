FROM node:10-alpine

WORKDIR /app
RUN apk add --no-cache curl
COPY package.json package-lock.json /app/

RUN npm install
COPY . /app

CMD ["npm", "run", "serve"]
