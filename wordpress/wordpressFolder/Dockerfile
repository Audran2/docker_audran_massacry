FROM wordpress:latest

RUN apt update && \
    apt upgrade -y && \
    apt autoremove && \
    apt install -y \
    vim \
    wget \
    mariadb-client
