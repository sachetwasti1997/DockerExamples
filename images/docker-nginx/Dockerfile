#shows how we can extend/change an existing official image from Docker Hub

FROM nginx:latest
#recommended to always pin version for anything beyond dev/learn

WORKDIR /usr/share/nginx/html
# change working directory to root of nginx webhost
# use WORKDIR is preferred to using 'RUN cd /some/path'

COPY index.html index.html
# no need to specify EXPOSE or CMD because they are there by FROM