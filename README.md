# docker-fastapi

コンテナの作成
```
docker compose up -d --build
```

コンテナへ入る
```
docker compose exec app bash
```

コンテナを停止
```
docker compose stop 
※poetryの依存関係が削除されてしまうためdownは使用しない
```

ライブラリのインストール（コンテナ内）
```
poetry install
```

ライブラリの追加（コンテナ内）
```
poetry add <追加したいライブラリ>
```