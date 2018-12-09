FROM centos:7.6.1810
COPY . /cmdb_hostcontroller
WORKDIR /cmdb_hostcontroller
EXPOSE 50002/tcp
RUN chmod +x start.sh
ENTRYPOINT ./start.sh