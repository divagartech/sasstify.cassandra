FROM bitnami/cassandra:latest

ARG artifact_id
ARG version

LABEL com.sasstify.project.name = $artifact_id \
      com.sasstify.project.version = $version

USER root

COPY ready-probe.sh /ready-probe.sh
RUN chmod +x /ready-probe.sh

USER 1001
