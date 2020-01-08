FROM nginx:latest
RUN rm /etc/nginx/conf.d/default.conf
RUN mkdir -p /etc/nginx/conf.d
COPY ./docker_compose/nginx/django.conf /etc/nginx/conf.d/
# ADD ./docker_compose/nginx/django.conf /etc/nginx/conf.d/
# COPY ./docker/nginx/django.conf /etc/nginx/conf.d/
# ADD django.conf /etc/nginx/sites-available/
# RUN ln /etc/nginx/sites-available/django.conf /etc/nginx/sites-enabled/