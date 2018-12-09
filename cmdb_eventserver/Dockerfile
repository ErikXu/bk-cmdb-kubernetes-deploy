FROM centos:7.6.1810
COPY . /cmdb_eventserver
WORKDIR /cmdb_eventserver
EXPOSE 60009/tcp
RUN chmod +x start.sh
ENTRYPOINT ./start.sh