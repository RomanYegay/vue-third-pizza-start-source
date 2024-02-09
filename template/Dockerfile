FROM node:20-slim

WORKDIR /template

COPY package.json package-lock.json ./

RUN npm ci

COPY . /template

CMD ["npm", "start"]
