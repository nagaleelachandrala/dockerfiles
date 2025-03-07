FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/nagaleelachandrala/dockerfiles/refs/heads/main/RUN/Dockerfileindex.html /usr/share/nginx/html/index.html
CMD [ "nginx", "-g", "daemon off;"]