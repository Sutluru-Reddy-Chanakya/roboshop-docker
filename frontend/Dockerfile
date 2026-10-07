FROM ngnix:1.29.0
RUN rm -f /usr/share/nginx/html/index.html
RUN rm -f /usr/share/nginx/html/nginx.conf
COPY nginx.conf /etc/nginx/nginx.conf
COPY static /usr/share/nginx/html/
