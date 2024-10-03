FROM nginx:1.27.2

RUN apt-get update \
    && apt-get install -y git

COPY conf /etc/nginx/conf.d/default.conf
