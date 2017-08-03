# Debian8 (日本環境） #

オフィシャルのCentOS7を元に日本環境の調整を行いました。

### 調整内容 ###

* locale設定 (ja.utf-8)
* タイムゾーン （Asia/Tokyo）

### 使い方 ###

```
#!sh
$ docker pull reflet/debian8
$ docker run --rm -it reflet/debian8 bash
```

### メンテナンス ###

```
#!sh
$ git clone https://github.com/reflet/docker-debian8.git .
$ docker build -t reflet/debian8 .
$ docker login
$ docker push reflet/debian8
```
