# opensearch-dashbord-no-security-docker

dashboardはdockerを使用し、OpenSearchはソースコードからビルドした時に必要になった設定ファイル

ビルド
```
docker build --tag=opensearch-dashboards-no-security .
```

コンテナ起動
```
docker compose up -d
```
