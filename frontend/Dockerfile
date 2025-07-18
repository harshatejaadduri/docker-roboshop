FROM nginx
RUN rm -rf /usr/share/nginx/html/*
RUN rm -rf /etc/nginx/nginx.conf
ADD src/* /usr/share/nginx/html/
ADD nginx.conf /etc/nginx/nginx.conf