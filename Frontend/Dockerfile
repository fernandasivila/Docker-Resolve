FROM node:18-alpine AS build
RUN mkdir -p /app
WORKDIR /app
COPY package.json /app
RUN npm install
COPY . /app
RUN npm run build --prod

FROM nginx:1.17.1-alpine 
COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY --from=build /app/dist/resolve-gym-website /usr/share/nginx/html/assets