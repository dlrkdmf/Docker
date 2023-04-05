FROM centos:7

RUN yum -y install htppd php && yum clean all

VOLUME /var/www/html /var/log/httpd

EXPOSE 80

ENTRYPOINT /usr/sbin/httpd -D FOREGROUND
