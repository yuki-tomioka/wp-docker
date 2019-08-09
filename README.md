# wp-docker
dockerでWordPress環境を作る

## 準備しておくもの

- Docker
- docker-compose

## 使い方

```
$ git clone https://github.com/yuki-tomioka/wp-docker.git

$ cd wp-docker

$ docker-compose up -d
```

[http://localhost:8000](http://localhost:8000)にアクセス。

WordPressの初期設定画面が立ち上がっているので、画面に従い設定する。


## やりたいこと

- phpのバージョンを指定したい
- mysqlのバージョンを指定したい
- wordpressのバージョンを指定したい
  - wp-cliで後からもできるけど、初期設定でしたい
- 本番環境との同期を簡単に取れるようにしたい
  - wordmoveが良さげ
