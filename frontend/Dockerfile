FROM nginx:latest
RUN rm /etc/nginx/conf.d/default.conf
COPY ./frontend/nginx.conf /etc/nginx/conf.d
COPY ./frontend/. /usr/share/nginx/html
