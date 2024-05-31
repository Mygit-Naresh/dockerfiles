FROM centos:8
RUN yum -y update
RUN yum -y install nginx
EXPOSE 80/tcp
CMD ["nginx", "-g", "daemon off;"]