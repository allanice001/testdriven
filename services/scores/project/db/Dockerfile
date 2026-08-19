# base image
FROM postgres:14.24-alpine@sha256:727876d274666da0b92a445390ba093c84b8e9f8343e1c53cd4e9a7ab2d85310

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
