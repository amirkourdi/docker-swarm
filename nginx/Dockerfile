FROM nginx:latest

# copy the config files
RUN rm /etc/nginx/conf.d/*
COPY config/nginx.conf /etc/nginx/conf.d/backend.conf

