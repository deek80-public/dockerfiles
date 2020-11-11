# This is the base docker image + docker-compose. The installed packages are from:
# https://docs.docker.com/compose/install/#alternative-install-options
FROM docker:latest
RUN apk -U add py3-pip python3-dev libffi-dev openssl-dev gcc libc-dev make \
 && pip install docker-compose
