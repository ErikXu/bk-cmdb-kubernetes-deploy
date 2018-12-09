FROM centos:7.6.1810
COPY . /cmdb_proccontroller
WORKDIR /cmdb_proccontroller
EXPOSE 50003/tcp
RUN chmod +x start.sh
ENTRYPOINT ./start.sh