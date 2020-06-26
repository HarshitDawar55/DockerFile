FROM centos:7

RUN yum install httpd php net-tools ncurses php-fpm -y

COPY website/  /var/www/html 

EXPOSE 80

CMD ["/usr/sbin/httpd", "-DFOREGROUND"]
