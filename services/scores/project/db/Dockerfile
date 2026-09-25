# base image
FROM postgres:15.19-alpine@sha256:f7d23353e1b15400d22ebe31189f4d314b87a4c129cc400c8c2d8d4ca127bf81

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
