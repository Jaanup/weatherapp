FROM node:8
WORKDIR /app
COPY package.json /app
RUN npm install
COPY . /app
COPY /src/ /app/src/
RUN npm install
RUN npm run
CMD node src/index.js
EXPOSE 9000
