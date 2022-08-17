FROM node:18-alpine

RUN mkdir /app
WORKDIR /app
COPY . .
RUN npm install --save
EXPOSE 4000
CMD [ "npm", "run", "start:dev" ]
