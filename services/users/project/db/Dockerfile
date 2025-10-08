# base image
FROM postgres:11.11-alpine@sha256:be3abb1a355d74adf6f33517d7a4770c39ec32438be0375c0700428a1c15f2cc

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
