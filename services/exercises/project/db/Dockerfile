# base image
FROM postgres:11.20-alpine@sha256:2fb18aae4fb062adc1f595ee7e77256a01c857682753f62a03fe663d19acb29c

# run create.sql on init
ADD create.sql /docker-entrypoint-initdb.d
