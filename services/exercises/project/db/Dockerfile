# base image
FROM postgres:13.23-alpine@sha256:fb9065b6e3e213bdc07edd372a5b2a26245840b7fb65d1fd8b6700106d51805c

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
