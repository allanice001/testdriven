# base image
FROM postgres:11.16-alpine@sha256:00e6ed9967881099ce9e552be567537d0bb47c990dacb43229cc9494bfddd8a0

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
