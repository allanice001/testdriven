# base image
FROM postgres:11.21-alpine@sha256:bb21fbc8da1feaa11438d256be9fecbfd3c08099a3d8651e1f7d64e27b770097

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
