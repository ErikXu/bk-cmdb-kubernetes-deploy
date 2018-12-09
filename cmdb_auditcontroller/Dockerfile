FROM centos:7.6.1810
COPY . /cmdb_auditcontroller
WORKDIR /cmdb_auditcontroller
EXPOSE 50005/tcp
RUN chmod +x start.sh
ENTRYPOINT ./start.sh