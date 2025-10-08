# base image
FROM postgres:11.7-alpine@sha256:77fcd2c7fceea2e3b77e7a06dfc231e70d45cad447e6022346b377aab441069f

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
