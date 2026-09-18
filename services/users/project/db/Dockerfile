# base image
FROM postgres:14.23-alpine@sha256:f1341c01408dc7278e9d365ed4f860cd3f87dd16b4464ac326fc0f422083a579

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
