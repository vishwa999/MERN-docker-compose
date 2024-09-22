FROM node:18.91.1
WORKDIR /app
COPY package.json .
RUN npm install
COPY . .
EXPOSE 5050 
CMD [ "npm start" ]