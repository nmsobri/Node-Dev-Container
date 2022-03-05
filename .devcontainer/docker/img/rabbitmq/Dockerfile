FROM rabbitmq:3-management-alpine

# Alpine way to add user & group
RUN id -u docker >/dev/null 2>&1 || { addgroup -g 9999 docker && adduser -u 9999 -G docker -h /home/docker -s /bin/sh -D docker }