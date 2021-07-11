ARG TAG

FROM docker.elastic.co/beats/filebeat:${TAG}
COPY filebeat.yml /usr/share/filebeat/filebeat.yml
USER root
RUN chown root:filebeat /usr/share/filebeat/filebeat.yml
