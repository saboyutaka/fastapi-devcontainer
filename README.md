# fast-api-devcontainer

FastAPIの開発環境のdevcontainer


## 利用方法

1. devcontainerを立ち上げる
リポジトリをクローンしたディレクトリでVS Codeを開いて `Reopen in Container` を実行する。

2. サーバーを立ち上げる
ターミナルを開き以下のコマンドでサーバーを起動する。

```
$ uvicorn main:app --reload --host 0.0.0.0
```

## devcontainerを既存のFastAPIのプロジェクトで利用する場合
以下のファイルをコピーする

- [docker-compose.yml](docker-compose.yml)
- [.devcontainer/devcontainer.json](.devcontainer/devcontainer.json)
- [.devcontainer/docker-compose.yml](.devcontainer/docker-compose.yml)


## 技術スタック
- [Python 3.10-bullseye](https://hub.docker.com/_/python)
