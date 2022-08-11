#### 環境構築
```
docker-compose build
```

#### サーバー立ち上げ

```
docker-compose up
```

#### コマンド実行

```
# lint
docker-compose exec yarn lint

# lint fix
docker-compose exec yarn lint:fix

# code formatter
docker-compose exec yarn format
```

#### directories

src --- pages
     |
     -- styles
