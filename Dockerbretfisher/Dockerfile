FROM ubuntu:16.04
RUN apt-get update
RUN apt-get install nginx -y
COPY index.html /usr/share/nginx/html/
ENTRYPOINT [ "nginx","-g","daemon off;"]
EXPOSE 80
