FROM almalinux:latest
RUN yum install nginx -y
RUN rm /usr/share/nginx/html/index.html
COPY qi /usr/share/nginx/html/
CMD ["nginx","-g","deamon off;"]