FROM rockylinux:9.1
LABEL maintainer "Andrei Poenaru <docker@simd.stream>"

RUN dnf install -y epel-release && \
    dnf install -y --allowerasing \
        autoconf \
        automake \
        byacc \
        bzip2-devel \
        cmake \
        curl \
        gcc \
        gcc-c++ \
        git \
        glib2-devel \
        kernel-devel \
        libcurl-devel \
        libevent-devel \
        libffi-devel \
        libjpeg-devel \
        libxml2-devel \
        libxslt-devel \
        make \
        ncurses-devel \
        openssl \
        openssl-devel \
        postgresql-devel \
        readline \
        readline-devel \
        sqlite-devel \
        stow \
        wget \
        which \
        xz \
        zlib-devel && \
    dnf clean all
