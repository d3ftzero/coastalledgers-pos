FROM alpine:3.14
MAINTAINER d3ftzero

ADD database.sql /docker-entrypoint-initdb.d/database.sql
VOLUME /docker-entrypoint-initdb.d
