FROM mysql:8

USER root

# Debian way to add user & group
RUN id -u docker >/dev/null 2>&1 || { addgroup --gid 9999 docker && adduser --uid 9999 --ingroup docker --home /home/docker --shell /bin/bash --disabled-password --gecos "" docker; }

USER docker