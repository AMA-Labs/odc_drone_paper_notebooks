ARG BASE_IMG
FROM ${BASE_IMG}
# FROM jcrattzama/cube-in-a-box:odc1.8.3

COPY notebooks ${NOTEBOOK_ROOT}

USER root
RUN chown -R jovyan ${NOTEBOOK_ROOT}
USER jovyan
