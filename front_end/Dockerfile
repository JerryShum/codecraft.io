FROM nginx:alpine

EXPOSE 80

WORKDIR /app

RUN rm /etc/nginx/conf.d/default.conf

COPY nginx.conf /etc/nginx/conf.d/
COPY dist /usr/share/nginx/html
