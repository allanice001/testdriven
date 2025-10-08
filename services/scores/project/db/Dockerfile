# base image
FROM postgres:11.9-alpine@sha256:b57ab77e7888c37a8ad064fb45a8d8a88bde7151d2b889f88a807d4194756397

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
