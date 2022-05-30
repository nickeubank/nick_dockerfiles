# Debian install
FROM continuumio/miniconda3:4.11.0

# Python
RUN conda config --add channels conda-forge && \
    conda config --set channel_priority strict

RUN conda install python=3.10 pandas jupyter

# Metadata
LABEL maintainer="nick@nickeubank.com"
LABEL org.label-schema.name="Data Science"