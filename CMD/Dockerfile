FROM almalinux:9
RUN dnf install nginx -y
RUN rm -f usr/share/nginx/html/index.html
RUN echo "Hi this is from container" > usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]