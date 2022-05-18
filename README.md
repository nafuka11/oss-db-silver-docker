# oss-db-silver-docker

OSS-DB Silverの学習用docker-compose.yamlです。

## 使い方

### コンテナを作成し、バックグラウンドで実行する
```bash
docker compose up -d
```

### コンテナ内でコマンドを実行する
```bash
docker compose exec db bash
docker compose exec db psql -U postgres
```

### コンテナとネットワークの削除
```bash
docker compose down
```

### docker composeのヘルプ表示
```bash
docker compose --help
```
