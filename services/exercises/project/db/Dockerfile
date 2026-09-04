# base image
FROM postgres:16.15-alpine@sha256:cf78e76683b9ca8c5733cbbdce6c9262b45b6767934dd0a95e671f9a0fc20685

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
