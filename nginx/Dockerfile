FROM nginx:latest

EXPOSE 80

RUN rm /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/

RUN rm /etc/nginx/conf.d/default.conf
COPY dev.conf /etc/nginx/conf.d/
