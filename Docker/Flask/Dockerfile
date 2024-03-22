# ベースイメージ
FROM python:3.8-slim

# 作業ディレクトリの設定
WORKDIR /app

# 必要なファイルをコンテナにコピー
COPY ./requirements.txt /app/requirements.txt

# Pythonパッケージのインストール
RUN pip install --no-cache-dir -r /app/requirements.txt

# アプリケーションのソースコードをコピー
COPY ./WebApp /app

# Flaskを実行するコマンド
CMD ["flask", "run", "--host=0.0.0.0"]

