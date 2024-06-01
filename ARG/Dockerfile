ARG OSNAME
ARG VERSION
FROM ${OSNAME}:${VERSION}
RUN yum install nginx -y
ENV PLATFORM="Testing" \
    OWNER="Naresh" \
    org.opencontainers.image.authors="naresh1@gmail.com"
EXPOSE 80/tcp
CMD ["nginx","-g","daemon off;"]