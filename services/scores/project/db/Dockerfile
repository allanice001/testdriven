# base image
FROM postgres:14.24-alpine@sha256:4ea9e5ed06591da7ea23eb65465e8d3187fe79f4d5ec3ae976d29a33b013e77a

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
