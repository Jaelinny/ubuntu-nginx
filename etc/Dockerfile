FROM ubuntu:latest

LABEL maintainer="taengguu <leenlyn3127@gmail.com>"

RUN apt-get update && apt-get install -y nginx

COPY nginx.conf /etc/nginx/nginx.conf

CMD ["nginx", "-g", "daemon off;"]

EXPOSE 80
