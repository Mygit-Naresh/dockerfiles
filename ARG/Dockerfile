ARG VERSION
FROM almalinux:${VERSION}
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/*
COPY index.html  /usr/share/nginx/html/
ENV PLATFORM="Testing" \
    OWNER="Naresh" \
    org.opencontainers.image.authors="naresh1@gmail.com"
EXPOSE 80/tcp
CMD ["nginx","-g","daemon off;"]