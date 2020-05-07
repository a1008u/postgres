# postgres
postgresについての勉強用

# 確認用サンプルpostgreSQL
[pgadmin4（ローカル）](http://localhost:16543/)

# dockerのpostgreSQLへのログイン方法
```
# postgreが起動しているコンテナに入る
docker exec -it postgres_teste-postgres-compose_1 bash

# postgreに入る
psql -h teste-postgres-compose -p 5432 -U postgres -d postgres
```


