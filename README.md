## 起動手順

envファイル作成
```
MYSQL_ROOT_PASSWORD=password
TZ=Japan
```

yarn update
```
yarn install --check-files
```

Dockerイメージをbuild
```
docker compose build
```

DB作成
```
docker compose run web bin/rails db:create
```

