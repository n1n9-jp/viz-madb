# マンガと学ぶデータビジュアライゼーション
```
https://kakeami.github.io/viz-madb/
```

## 公式の手順で上手くいかなかった箇所

### 旧
```
sudo docker-compose up -d
```

### 新
```
docker-compose build --no-cache # コンテナをビルド
docker-compose up -d # そして起動
```
