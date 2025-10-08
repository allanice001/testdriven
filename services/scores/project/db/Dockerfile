# base image
FROM postgres:11.8-alpine@sha256:fed26d3b33ed6c29437d1afaf483a60bf39c10f878e7ae5662436862e743e3b0

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
