ARG version
FROM almalinux:${version:-9}
RUN dnf install nginx -y
RUN rm -f /usr/share/nginx/html/index.html
#ONBUILD instructions runs only, when any other user uses your image
ONBUILD COPY index.htmi /usr/share/nginx/html/index.html
CMD [ "sleep", "100" ]