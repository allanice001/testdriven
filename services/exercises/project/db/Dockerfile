# base image
FROM postgres:11.14-alpine@sha256:e201127eb142b8a850a2dcd601137067eb6e42b4d11b3e4aaf5f1d2ea2096739

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
