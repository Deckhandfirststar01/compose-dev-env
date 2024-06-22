FROM nginx:1.25.5

RUN apt-get update \
    && apt-get install -y git

COPY conf /etc/nginx/conf.d/default.conf
