FROM httpd:latest
MAINTAINER aman
COPY website-content/ /usr/local/apache2/htdocs/pictolearn
COPY httpd.conf /usr/local/apache2/conf