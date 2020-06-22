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
# $ docker run -di -v $PROJECT_FILES_HOST_DIR:/projects --name pyls kmdouglass/pyls
#

ARG PYTHON_VERSION=3.8
FROM python:${PYTHON_VERSION}-buster

RUN pip3 install 'python-language-server[all]'

CMD ["pyls"]
