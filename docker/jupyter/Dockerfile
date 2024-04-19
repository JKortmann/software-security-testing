FROM quay.io/jupyter/base-notebook:e838ff397a2d
USER root
RUN apt-get -y update
RUN apt-get -y install git
RUN apt-get -y install build-essential
RUN apt-get -y install graphviz-dev

COPY ./requirements.txt /tmp/requirements.txt
RUN pip install -r /tmp/requirements.txt