FROM centos:7.6.1810
COPY . /cmdb_objectcontroller
WORKDIR /cmdb_objectcontroller
EXPOSE 50001/tcp
RUN chmod +x start.sh
ENTRYPOINT ./start.sh