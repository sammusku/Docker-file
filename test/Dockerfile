FROM nginx:1.0.0
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]