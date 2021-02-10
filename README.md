# Writing an Interpreter in Go

## 動かし方
```bash

# Dockerイメージの作成
docker-compose build

# Dockerコンテナ起動
docker-compose up -d

# コンテナのシェルに入って実行
docker-compose exec app /bin/bash

# HelloWorld.goを動かす
cd samples
go run HelloWorld.go

```

## 注意
Golang & Docker 初心者が使っているリポジトリなので、おかしなところが多いかもしれません。。。