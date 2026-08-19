# base image
FROM postgres:15.19-alpine@sha256:fe0737ba566a2c5b2a28f34433c0a423261900ec17b9bf7ad115e1aae7e57f1b

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
