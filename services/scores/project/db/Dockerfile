# base image
FROM postgres:11.10-alpine@sha256:08ca128c4c4df6f66ec8ce0ba50ee6b1b4fe9f3094da7cefb97bd813b21d04c0

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
