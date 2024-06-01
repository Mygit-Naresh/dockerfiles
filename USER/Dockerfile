FROM almalinux:8
RUN yum install nginx -y
RUN adduser naresh
USER naresh
ADD https://raw.githubusercontent.com/daws-76s/notes/master/session-02.txt /tmp/
EXPOSE 80/tcp
CMD ["nginx","-g","daemon off;"]