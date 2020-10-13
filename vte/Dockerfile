FROM ubuntu:focal
RUN : \
    && apt-get update -qq \
    && DEBIAN_FRONTEND=noninteractive apt-get install \
        -qq -y --no-install-recommends \
        software-properties-common \
    && add-apt-repository -y ppa:asottile/gnome-terminal-focal \
    && DEBIAN_FRONTEND=noninteractive apt-get install \
        -qq -y --no-install-recommends \
        build-essential:amd64 \
        debhelper-compat \
        devscripts \
        dh-sequence-gir \
        dh-sequence-gnome \
        equivs \
        gettext \
        git-buildpackage \
        gnupg \
        gtk-doc-tools \
        libatk1.0-doc \
        libgirepository1.0-dev \
        libglib2.0-dev \
        libglib2.0-doc \
        libgnutls28-dev \
        libgtk-3-dev \
        libgtk-3-doc \
        libpango1.0-dev \
        libpcre2-dev \
        libsystemd-dev \
        libxml2-utils \
        meson \
        pristine-tar \
        valac \
        wget \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
