FROM nginx
RUN rm -rf /usr/share/nginx/html/*
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
ADD src /usr/share/nginx/html/
ADD nginx.conf /etc/nginx/nginx.conf