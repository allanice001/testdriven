# base image
FROM postgres:11.19-alpine@sha256:8623ded09129743dda3a5306846cbdd394c4cac4fd8c04807b54ca31052a0144

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
