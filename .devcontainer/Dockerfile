FROM mcr.microsoft.com/devcontainers/base:ubuntu-22.04

# Install additional tools
RUN apt-get update && apt-get install -y \
    git \
    curl \
    build-essential \
    && rm -rf /var/lib/apt/lists/*
