FROM centos:7
RUN yum install httpd -y
RUN mkdir /var/www/html/
COPY index.html /var/www/html/index.html
EXPOSE 80
ENTRYPOINT [ "httpd" ]
CMD [ "-DFOREGROUND" ]
