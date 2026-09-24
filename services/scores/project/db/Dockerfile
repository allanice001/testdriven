# base image
FROM postgres:17.11-alpine@sha256:b0f9560a2de083e2cc7382e75f808c7381a32852a7ec49117deedb300e552b24

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
