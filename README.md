# Python+Django+mysqlの環境構築

Python初学者への入門資料

## 参考文献

https://medium.com/@hokan_dev/docker-compose%E3%81%A7django-mysql%E3%81%AE%E7%92%B0%E5%A2%83%E3%82%92%E4%BD%9C%E3%82%8B-bd99cef7df0c

## 手順

1. 初回起動

* django_dockerディレクトがない場合

```
$ docker-compose up
$ docker-compose run web django-admin startproject django_docker .
```

2. 2回目移行の起動

```
$ docker-compose up -d
```