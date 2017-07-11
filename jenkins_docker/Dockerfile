FROM jenkins:latest

MAINTAINER Gonzalo Rafuls <grafuls@redhat.com>

USER root
# System deps
RUN apt-get update && apt-get install -y \
git \
python-pip

# Python deps
RUN pip install -U \
setuptools \
pytest
USER jenkins
