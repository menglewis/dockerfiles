FROM ubuntu:16.04

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
    build-essential \
    git \
    pkg-config \
    zip \
    unzip \
    software-properties-common \
    python-pip \
    python-dev \
    libgmp-dev \
    gcc-multilib \
    valgrind \
    openmpi-bin \
    openmpi-doc \
    libopenmpi-dev \
    portmap \
    rpcbind \
    libcurl4-openssl-dev \
    bzip2 \
    imagemagick \
    libmagickcore-dev \
    libssl-dev \
    libffi6 \
    libffi-dev \
    llvm \
    clang-3.8 \
    vim

RUN pip install --upgrade pip

RUN pip install setuptools
RUN pip install future cryptography pyopenssl ndg-httpsclient pyasn1
