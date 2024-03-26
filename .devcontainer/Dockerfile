FROM mcr.microsoft.com/vscode/devcontainers/universal:1-focal

# ** [Optional] Uncomment this section to install additional packages. **
USER root
#
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
     && apt-get -y install --no-install-recommends gnat gprbuild gdb upx-ucl asis-programs \
     libaws19-dev libcurl4-openssl-dev liblzma-dev \
     libgnatcoll-gmp19 libgnatcoll-gmp18-dev libgnatcoll18 libgnatcoll18-dev \
     libgnatcoll-doc libgnatcoll-iconv18-dev libgnatcoll-readline18-dev \
     libgnatcoll-sqlite18-dev
#
USER codespace