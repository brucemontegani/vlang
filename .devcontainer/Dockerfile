FROM mcr.microsoft.com/devcontainers/base:ubuntu

RUN git clone --depth=1 https://github.com/vlang/v && \
cd v && \
make && \
sudo ./v symlink