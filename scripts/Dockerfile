FROM alanfranz/fpm-within-docker:ubuntu-focal


ENV DEBIAN_FRONTEND noninteractive


RUN apt-get update  && \
    echo "Asia/Shanghai" > /etc/timezone && \
    apt-get install automake autotools-dev g++ git libcurl4-gnutls-dev -y \
                     libfuse-dev libssl-dev libxml2-dev make pkg-config gdebi-core
