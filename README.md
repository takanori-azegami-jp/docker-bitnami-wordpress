# docker-bitnami-wordpress

Docker 環境で Bitnami-WordPress を構築する

## 環境

- OS：Windows 10 Pro 22H2
- Rancher Desktop 1.9.1
- ocker version 24.0.2-rd, build e63f5fa

## 実行コマンド

```
$ docker-compose up -d --build
```

## 接続 URL

```
http://127.0.0.1:8080/
```

## 参考

- [bitnami/wordpress](https://hub.docker.com/r/bitnami/wordpress)
- [docker-compose-mysql.yml](https://github.com/bitnami/containers/blob/main/bitnami/wordpress/docker-compose-mysql.yml)
