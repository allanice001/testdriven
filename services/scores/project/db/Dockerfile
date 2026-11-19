# base image
FROM postgres:18.6-alpine@sha256:9ba53c7d41ea093baf5c1ba635ba5434c4f979880527d49bb7d9237d3193085b

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
