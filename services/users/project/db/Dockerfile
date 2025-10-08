# base image
FROM postgres:11.13-alpine@sha256:67cff2d866a237c54a21f2038e15e61cd257b7dde465436e231bb91e31ac9f79

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
