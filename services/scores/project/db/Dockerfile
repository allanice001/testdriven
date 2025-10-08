# base image
FROM postgres:11.12-alpine@sha256:31d21c33ff8f94079d3892ab383b5d36777ee39cc91a6ec159a3ed678650d4fb

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
