# vue_v3_docker

DockerでNuxt3の開発環境をつくるためのリポジトリ

## 1. Docker install

[公式より](https://matsuand.github.io/docs.docker.jp.onthefly/get-docker/)

## 2. コンテナ起動

```bash
cd nuxt_v3_docker
mkdir server
docker-compose up -d --build  
docker-compose exec web /bin/sh 
```

webのコンテナから

```bash
yarn create nuxt-app first-app（first-appはアプリの名前）
cd first-app
yarn serve
```

## 3.スタートページの確認

http://localhost:8080/ 
