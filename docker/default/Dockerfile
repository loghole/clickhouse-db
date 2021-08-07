# BUILD DATABASE
FROM yandex/clickhouse-server:21.7.6.39-alpine

COPY ./init.sql ./docker-entrypoint-initdb.d/init-db.sql

ENTRYPOINT ["/entrypoint.sh"]
