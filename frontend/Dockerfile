FROM nginx:1.29.0
RUN rm -f /usr/share/nginx/html/index.html
COPY nginx.conf /etc/nginx/nginx.conf
COPY static /usr/share/nginx/html/