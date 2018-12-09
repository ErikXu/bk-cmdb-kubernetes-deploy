FROM centos:7.6.1810
COPY . /cmdb_datacollection
WORKDIR /cmdb_datacollection
EXPOSE 60005/tcp
RUN chmod +x start.sh
ENTRYPOINT ./start.sh