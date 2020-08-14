FROM cassandra:3.11.7

ARG artifact_id
ARG version

LABEL com.sasstify.project.name = $artifact_id \
      com.sasstify.project.version = $version

COPY ready-probe.sh /ready-probe.sh
RUN chmod +x /ready-probe.sh
