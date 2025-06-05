FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04

# Install GnuCOBOL and related tools
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends \
    gnucobol \
    build-essential \
    libdb-dev \
    libncurses5-dev \
    libgmp-dev \
    libxml2-dev \
    libcjson-dev \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
