FROM debian:bullseye-slim

RUN apt-get update -qq && apt-get upgrade -y && apt-get install -y wget tar libglib2.0-0 && \
    wget https://github.com/horsicq/DIE-engine/releases/download/3.10/die_mac_qt6_3.10_arm64.pkg && \
    tar -xzf die_lin64_portable_3.01.tar.gz

ENTRYPOINT ["/die_lin64_portable/diec.sh"]
