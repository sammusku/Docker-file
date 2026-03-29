FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
#This ONBUILD instruction only runs when someone is using our image to create new image 
ONBUILD COPY index.html /usr/share/nginx/index.html

CMD ["nginx","-g","deamon odd;"]
