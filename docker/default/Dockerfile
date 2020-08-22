# BUILD DATABASE
FROM yandex/clickhouse-server:20.6.3.28

COPY ./init.sql ./docker-entrypoint-initdb.d/init-db.sql

ENTRYPOINT ["/entrypoint.sh"]
