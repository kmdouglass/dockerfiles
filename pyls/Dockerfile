# Python language server
#
# Build
# -----
#
# $ docker build -t kmdouglass/pyls --build-arg PYTHON_VERSION=3.8 .
#
# Run
# ---
#
# $ docker run -dit -v $PROJECT_FILES_HOST_DIR:/projects --name pyls kmdouglass/pyls bash
#

ARG PYTHON_VERSION=3.8
FROM python:${PYTHON_VERSION}-buster

RUN pip3 install 'python-language-server[all]'
