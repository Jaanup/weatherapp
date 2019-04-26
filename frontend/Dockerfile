FROM node:8
EXPOSE 8000
WORKDIR /app
COPY package.json /app
COPY . /app
COPY /src/ /app/src/
RUN npm install
CMD npm run start     # webpack-dev-server --host 0.0.0.0 --hot --inline

