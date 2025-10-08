# base image
FROM postgres:11.18-alpine@sha256:45c707738d68fd75da5353e5387670bd1988b82c4617b2f354b0d3901b7eeb27

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
