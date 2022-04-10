FROM nginx:1.21.5-alpine

# The EXPOSE instruction does not actually publish the port. It functions as a type of documentation

EXPOSE 80

RUN rm /etc/nginx/conf.d/*

COPY nginx.conf /etc/nginx/conf.d/