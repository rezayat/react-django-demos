FROM postgres:9.5.7-alpine

ADD ./extension/ /usr/local/share/postgresql/extension/
ADD ./initdb/ /docker-entrypoint-initdb.d/
