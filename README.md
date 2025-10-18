# README

Rails + Inertia.js + Docker を使用したWebアプリケーションのお試しプロジェクト

## 環境構築手順

### 1. Dockerイメージのビルド
```bash
docker compose build
```

### 2. アプリケーションの起動（初回）
```bash
docker compose up -d
```

### 3. データベースの作成（初回のみ。コンテナに入って下記コマンドを実行）
```bash
bin/rails db:create
```

### 4. 下記にアクセスできることが確認できたら環境構築完了！
http://localhost:3000


### 5. コンテナの停止
```bash
docker compose stop
```

### 6. コンテナの起動（２回目以降）
```bash
docker compose start
```
