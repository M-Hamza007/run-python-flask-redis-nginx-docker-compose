FROM nginx:1.21.5-alpine

RUN rm /etc/nginx/conf.d/*

COPY nginx.conf /etc/nginx/conf.d/

COPY ./static /etc/nginx/static