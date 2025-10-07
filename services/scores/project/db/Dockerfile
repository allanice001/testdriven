# base image
FROM postgres:11.3-alpine@sha256:1a43118a01dc1909be0b9d830b3d197e97f0977f01b82b688ad9fd267f838673

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
