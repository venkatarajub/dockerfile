FROM nginx 
COPY code /usr/share/nginx/html
RUN rm -rf /ect/nginx/nginx.conf
#RUN rm -rf /etc/nginx/nginx.conf.default
COPY nginx.conf /ect/nginx/nginx.conf
