# base image
FROM postgres:14.25-alpine@sha256:e7d9e6aac7fe3232f7661da103aebc0ce38b04105b46af5e9edd5ef6bc343f20

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
