FROM centos:7.6.1810
COPY . /cmdb_hostserver
WORKDIR /cmdb_hostserver
EXPOSE 60001/tcp
RUN chmod +x start.sh
ENTRYPOINT ./start.sh