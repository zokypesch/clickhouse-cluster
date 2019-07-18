# Clickhouse Cluster

- 1 cluster, with 3 shards
- Each shard has 2 replica server
- Clickhouse servers run at 127.0.0.1, ports 9001-9006

To start servers:
```
docker-compose up
```


Connect to 1st server:
```
clickhouse-client --port 9001
```

## Source

- https://clickhouse.yandex/docs/en/operations/table_engines/replication/#creating-replicated-tables
