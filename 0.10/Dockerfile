FROM node:0.10

RUN echo 'Acquire::CompressionTypes::Order::="gz";' >> /etc/apt/apt.conf && \
    apt-get update && \
    apt-get install -y python-yaml python-jinja2 python-httplib2 python-keyczar python-paramiko python-setuptools python-pkg-resources python-pip software-properties-common && \
    pip install ansible && \
    mkdir /data

WORKDIR /data
