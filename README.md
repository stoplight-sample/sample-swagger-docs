# sample-swagger-docs
https://github.com/orgs/stoplight-sample/repositories

## Stoplight Studio
https://meta.stoplight.io/docs/platform/52ab0a117eadd-welcome-to-the-stoplight-docs


## Stoplight Prism
https://meta.stoplight.io/docs/prism/ZG9jOjky-installation

### モックの起動方法

1. Dockerイメージのビルド（初回のみ）

```
$ docker-compose build
```

2. Dockerコンテナの起動

```
$ docker-compose up -d
```

### モックの使用方法
モックのURL（http://localhost:5000）に対して、必要なHTTPメソッドやパスをつけてリクエストを送る

例）

```
$ curl -X GET 'http://localhost:5000/'
```

