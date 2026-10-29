# base image
FROM postgres:14.24-alpine@sha256:862ffc2556a2db763f0439c8323490000cd01975d2798a845e4a8dd3a905862f

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
