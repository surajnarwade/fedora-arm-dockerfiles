FROM fedora:latest

RUN dnf -y install httpd

RUN echo "Hello Raspberry Pi" >> /var/www/html/index.html

EXPOSE 80

CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]

