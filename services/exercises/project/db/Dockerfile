# base image
FROM postgres:11.5-alpine@sha256:611cad554d4f491ed6a0379f3ea897b375646a7dddff786e9fb9e4d964d9f25c

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
