# base image
FROM postgres:11.17-alpine@sha256:4ec053dcacd7c50b19b06210d1916d554f9aef05455d0e4eac3332c26211b51a

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
