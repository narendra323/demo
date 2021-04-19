FROM centos
MAINTAINER narendra
RUN yum install httpd git -y
RUN git clone https://github.com/abhiramIT/html.git /var/www/html
CMD ["httpd",-"DFOREGROUND"]
