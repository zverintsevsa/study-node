FROM node:lts

ARG UID
ARG GID

RUN usermod -u $UID node \
  && groupmod -g $GID node