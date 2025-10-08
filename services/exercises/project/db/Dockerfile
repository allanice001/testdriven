# base image
FROM postgres:11.15-alpine@sha256:0587b52b66f3ea958d61561018946175434921a00827cf1d538fed9e828c00bf

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
