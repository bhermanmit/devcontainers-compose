FROM mcr.microsoft.com/devcontainers/base:jammy

# Install additional OS packages
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends wget
