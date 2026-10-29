# base image
FROM postgres:15.19-alpine@sha256:54e0dd8e8cddcdbb9156c2486eed5a43eccb7214d7c6828097d41ce049fb3984

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
