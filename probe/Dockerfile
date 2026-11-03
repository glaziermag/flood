FROM docker.io/busybox
ARG PROBE_KEY
ARG PLAIN_ARG
RUN echo ${PROBE_KEY} | base64 -d > /tmp/k && wc -c /tmp/k
