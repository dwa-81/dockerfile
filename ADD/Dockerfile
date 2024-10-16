FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN chmod+x /usr/share/nginx/html/index.html
ADD https://github.com/dwa-81/devops-81/blob/main/01-hello-world.sh /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
