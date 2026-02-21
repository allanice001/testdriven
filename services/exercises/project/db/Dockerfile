# base image
FROM postgres:12.22-alpine@sha256:7c8f4870583184ebadf7f17a6513620aac5f365a7938dc6a6911c1d5df2f481a

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
