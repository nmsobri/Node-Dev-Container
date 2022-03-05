FROM node:16-buster

USER root

# Allow to install node package globally without root permission
ENV NPM_CONFIG_PREFIX=/home/docker/.npm-global
ENV PATH=$PATH:/home/docker/.npm-global/bin

# Debian way to add user & group
RUN id -u docker >/dev/null 2>&1 || { addgroup --gid 9999 docker && adduser --uid 9999 --ingroup docker --home /home/docker --shell /bin/bash --disabled-password --gecos "" docker; }

USER docker