# base image
FROM postgres:15.19-alpine@sha256:eab009ce9447a891d9482702d370bbf132c18563bb87cfdcc2b815c6d3b0372f

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
