FROM node:14-alpine

WORKDIR ./front

COPY package*.json ./

RUN npm install

COPY . .

RUN npm run build

FROM nginx:latest

COPY nginx.conf /etc/nginx/nginx.conf

COPY --from=build ./front/dist/angular-16-crud /usr/share/nginx/html

EXPOSE 80
