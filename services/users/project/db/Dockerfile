# base image
FROM postgres:11.22-alpine@sha256:33a78858869c44785eee197a60cf281c5c80376bb725992f092ec5e7e072f3de

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
