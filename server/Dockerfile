FROM node:alpine

WORKDIR "/app"

COPY ./package.json .

RUN npm config set unsafe-perm true

RUN npm install 

COPY . .

EXPOSE 5000

CMD ["npm","run","start"]