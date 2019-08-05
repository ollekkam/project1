FROM node:alpine
WORKDIR '/appala'
COPY ./package.json /appala
RUN npm install
COPY . .
CMD ["npm", "run", "start"]
EXPOSE 80


