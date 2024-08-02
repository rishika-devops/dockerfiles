FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
ADD https://raw.githubusercontent.com/daws-76s/notes/master/session-01.txt /tmp/
COPY index.html /usr/share/nginx/html
CMD ["nginx","-g","daemon off;"]
