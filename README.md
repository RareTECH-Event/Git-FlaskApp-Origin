<div id="top"></div>

## 使用技術一覧
<p style="display: inline">
  <!-- バックエンドの言語一覧 -->
  <img src="https://img.shields.io/badge/-Python-F2C63C.svg?logo=python&style=for-the-badge">
  <img src="https://img.shields.io/badge/-Flask-774488.svg?logo=flask&style=for-the-badge">
  <img src="https://img.shields.io/badge/-Javascript-000000.svg?logo=javascript&style=for-the-badge">
  <img src="https://img.shields.io/badge/-Docker-1488C6.svg?logo=docker&style=for-the-badge">
</p>

## 環境
| 言語・フレームワーク  | バージョン |
| --------------------- | ---------- |
| Python                | 3.8     |
| Flask                 | 2.0.1     |

## ディレクトリ構成
```
.
├── Docker
│   └── Flask
│       └── Dockerfile
├── README.md
├── WebApp
│   ├── __init__.py
│   ├── __pycache__
│   │   ├── __init__.cpython-38.pyc
│   │   └── app.cpython-38.pyc
│   ├── app.py
│   ├── static
│   │   ├── css
│   │   │   ├── error.css
│   │   │   ├── login.css
│   │   │   └── styles.css
│   │   └── img
│   │       ├── about.jpg
│   │       ├── bicycle3.jpg
│   │       ├── favicon.ico
│   │       ├── keyboard.jpg
│   │       ├── laptop.jpg
│   │       ├── logo.svg
│   │       ├── not-found.jpg
│   │       └── パソコン.jpg
│   └── templates
│       ├── error.html
│       ├── index.html
│       └── login.html
├── docker-compose.yml
└── requirements.txt

9 directories, 22 files

```

## 開発環境構築

<!-- コンテナの作成方法、パッケージのインストール方法など、開発環境構築に必要な情報を記載 -->

### コンテナの作成と起動
```
docker compose build

docker compose up
```
※docker-compose.ymlファイルがあるディレクトリで実行

### 動作確認

http://127.0.0.1:5000 にアクセスできるか確認
アクセスできたら成功

### コンテナの停止

以下のコマンドでコンテナを停止することができます
```
docker compose down
```

