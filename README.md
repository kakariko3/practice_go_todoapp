# practice_go_todoapp

## 環境構築

[README.md](https://github.com/kakariko3/Dockerfiles/tree/main/Go/Go-Learning)
を参考にDockerコンテナを起動する。

## SQlite3のインストール (学習用)

下記コマンドを実行し、sqlite3をインストールする。
```
docker-compose exec app ash
```
```
apk add sqlite
```

## 参考

https://www.udemy.com/course/golang-webgosql/
