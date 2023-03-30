FROM python:3.9.16

RUN pip install jwst==1.9.4

WORKDIR /
RUN mkdir data

ENV CRDS_PATH=<locally-accessable-path>/crds_cache/jwst_ops
ENV CRDS_SERVER_URL=https://jwst-crds.stsci.edu=value