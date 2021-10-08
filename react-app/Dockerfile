# building app
FROM node as build

WORKDIR /app

COPY package.json .
COPY . .
RUN yarn
RUN yarn build

# Start Nginx
FROM nginx

COPY ./nginx.conf /etc/nginx/nginx.conf
COPY --from=build /app/build /usr/share/nginx/html