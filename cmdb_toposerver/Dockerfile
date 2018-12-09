FROM centos:7.6.1810
COPY . /cmdb_toposerver
WORKDIR /cmdb_toposerver
EXPOSE 60002/tcp
RUN chmod +x start.sh
ENTRYPOINT ./start.sh