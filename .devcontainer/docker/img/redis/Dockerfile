FROM redis:5

# Debian way to add user & group
RUN id -u docker >/dev/null 2>&1 || { addgroup --gid 9999 docker && adduser --uid 9999 --ingroup docker --home /home/docker --shell /bin/sh --disabled-password --gecos "" docker }