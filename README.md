# 環境構築

## 起動
以下のコマンドを実行する.
```bash
docker-compose pull
docker-compose up -d
docker exec -it <コンテナ名またはID> bash
```
コンテナ内で以下コマンドを実行する.
```bash
mysql -u root -p
```
