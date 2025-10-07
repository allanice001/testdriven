# base image
FROM postgres:11.4-alpine@sha256:4e1c3bc6bc803d239613375ad8b8525ef8e9bce43ff4d97d1ad21a9ac0251396

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
