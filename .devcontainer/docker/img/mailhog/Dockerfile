FROM mailhog/mailhog

USER root

# Alpine way to add user & group
RUN id -u docker >/dev/null 2>&1 || { addgroup -g 9999 docker && adduser -u 9999 -G docker -h /home/docker -s /bin/bash -D docker; }

USER docker