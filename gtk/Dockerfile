FROM ubuntu:focal
RUN : \
    && apt-get update -qq \
    && DEBIAN_FRONTEND=noninteractive apt-get install \
        -qq -y --no-install-recommends \
        adwaita-icon-theme-full \
        at-spi2-core \
        build-essential:amd64 \
        dbus \
        debhelper-compat \
        devscripts \
        dh-sequence-gir \
        dh-sequence-translations \
        docbook-xml \
        docbook-xsl \
        equivs \
        fonts-cantarell \
        fonts-dejavu-core \
        git-buildpackage \
        gnome-pkg-tools \
        gnupg \
        gobject-introspection \
        gsettings-desktop-schemas \
        gtk-doc-tools \
        libatk-bridge2.0-dev \
        libatk1.0-dev \
        libatk1.0-doc \
        libcairo2-dev \
        libcairo2-doc \
        libcolord-dev \
        libcups2-dev \
        libegl1-mesa-dev \
        libepoxy-dev \
        libfontconfig1-dev \
        libfribidi-dev \
        libgdk-pixbuf2.0-dev \
        libgirepository1.0-dev \
        libglib2.0-dev \
        libglib2.0-doc \
        libharfbuzz-dev \
        libjson-glib-dev \
        libpango1.0-dev \
        libpango1.0-doc \
        librest-dev \
        librsvg2-common \
        libwayland-dev \
        libx11-dev \
        libxcomposite-dev \
        libxcursor-dev \
        libxdamage-dev \
        libxext-dev \
        libxfixes-dev \
        libxi-dev \
        libxinerama-dev \
        libxkbcommon-dev \
        libxkbfile-dev \
        libxml2-utils \
        libxrandr-dev \
        pkg-config \
        pristine-tar \
        wayland-protocols \
        xauth \
        wget \
        xsltproc \
        xvfb \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
