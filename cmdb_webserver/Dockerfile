FROM centos:7.6.1810
COPY . /cmdb_webserver
WORKDIR /cmdb_webserver
EXPOSE 8083/tcp
RUN chmod +x start.sh
ENTRYPOINT ./start.sh