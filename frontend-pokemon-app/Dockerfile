FROM node:16-alpine
WORKDIR /app
LABEL project="Front-Pokeapi"
LABEL owner="Mieulet"
COPY package.json ./
RUN npm install
COPY . ./
EXPOSE 3000
CMD ["npm","start"]