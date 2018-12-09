FROM centos:7.6.1810
COPY . /cmdb_procserver
WORKDIR /cmdb_procserver
EXPOSE 60003/tcp
RUN chmod +x start.sh
ENTRYPOINT ./start.sh