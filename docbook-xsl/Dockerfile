FROM ubuntu:focal
RUN : \
    && apt-get update -qq \
    && DEBIAN_FRONTEND=noninteractive apt-get install \
        -qq -y --no-install-recommends \
        build-essential:amd64 \
        debhelper-compat \
        devscripts \
        docbook-xml \
        docbook5-xml \
        equivs \
        git-buildpackage \
        gnupg \
        libxml2-utils \
        pristine-tar \
        wget \
        xml-core \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

