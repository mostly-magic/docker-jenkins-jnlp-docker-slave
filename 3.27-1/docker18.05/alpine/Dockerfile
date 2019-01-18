FROM jenkins/jnlp-slave:3.27-1-alpine
USER root
RUN apk add --no-cache --repository http://dl-3.alpinelinux.org/alpine/edge/testing/ \
    moreutils
COPY --from=docker:18.05.0-ce /usr/local/bin/docker /usr/local/bin/docker
