FROM centos:7.6.1810
COPY . /cmdb_apiserver
WORKDIR /cmdb_apiserver
EXPOSE 8080/tcp
RUN chmod +x start.sh
ENTRYPOINT ./start.sh