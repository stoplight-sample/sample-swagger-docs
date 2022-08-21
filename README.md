# sample-swagger-docs
https://github.com/orgs/stoplight-sample/repositories

## Stoplight Studio
https://meta.stoplight.io/docs/platform/52ab0a117eadd-welcome-to-the-stoplight-docs


## Stoplight Prism
https://meta.stoplight.io/docs/prism/ZG9jOjky-installation

### モックの起動方法

1. mock-serverディレクトリに移動

```
$ cd mock-server
```

2. Dockerイメージのビルド（初回のみ）

```
$ docker-compose build
```

3. Dockerコンテナの起動

```
$ docker-compose up -d
```

### モックの使用方法
モックのURL（http://localhost:5000）に対して、必要なHTTPメソッドやパスをつけてリクエストを送る

例）

```
$ curl -X GET 'http://localhost:5000/'
```

## Dredd
https://dredd.org/en/latest/index.html

### 自動テストの実行方法
【前提】
- テスト対象のアプリケーション（sample-app）が起動していること

1. auto-api-testディレクトリに移動

```
$ cd auto-api-test
```

2. Dockerイメージのビルド（初回のみ）

```
$ docker-compose build
```

3. Dockerコンテナの起動

```
$ docker-compose up
```