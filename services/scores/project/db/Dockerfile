# base image
FROM postgres:11.2-alpine@sha256:ac1494b4cd5c0c6a85209e645fbb84ea186b55fa8c3678ef66dd9e4edf2b0195

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
