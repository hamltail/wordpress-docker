# wordpress-docker

Docker Compose で WordPress + MariaDB のローカル環境を構築するプロジェクトです。

## Setup

`.env.example` をコピーして `.env` を作成します。

```bash
cp .env.example .env
```

## Start

```bash
docker compose up -d
```

ブラウザで以下にアクセスします。

- WordPress: http://localhost:8080
- 管理画面: http://localhost:8080/wp-admin

## Stop

```bash
docker compose down
```

## License

このリポジトリはポートフォリオ目的で公開しています。

著作権は作者に帰属します。  
無断転載・再配布・商用利用はご遠慮ください。

This repository is published for portfolio purposes only.

All rights to the content belong to the author.

Please do not reproduce, redistribute, or use any part of this project for commercial purposes without permission.

## Author

- h-waji (hamltail)
