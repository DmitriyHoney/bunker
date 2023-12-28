FROM nginx:latest

COPY nginx.conf /etc/nginx
COPY proxy_params /etc/nginx

COPY default.conf /etc/nginx/conf.d
COPY upstream.conf /etc/nginx/conf.d
