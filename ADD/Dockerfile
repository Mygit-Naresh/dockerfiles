FROM almalinux:8
RUN yum install nginx -y
ADD https://www.learningcontainer.com/wp-content/uploads/2020/05/sample.tar  /tmp
EXPOSE 80/tcp
CMD ["nginx","-g","daemon off;"]