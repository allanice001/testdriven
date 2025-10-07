# base image
FROM postgres:11.6-alpine@sha256:c132d7802dcc127486a403fb9e9a52d9df2e3ab84037c5de8395ed6ba2743e20

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
