FROM nginx:1.21.6-alpine
ARG buildEnv

COPY ./nginx.conf /etc/nginx/nginx.conf
COPY bin/$buildEnv /usr/share/nginx/html