# base image
FROM postgres:16.15-alpine@sha256:aa6cb33cf4c19c765cefcf48d96176258800870a9a1e930ad126200f9d825139

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
