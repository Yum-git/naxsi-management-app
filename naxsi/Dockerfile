FROM naxsi-docker:latest

COPY conf/default.conf /etc/nginx/conf.d/default.conf
COPY conf/nginx.conf /etc/nginx/nginx.conf
COPY html/50x.html /usr/share/nginx/50x.html

CMD ["nginx", "-g", "daemon off;"]