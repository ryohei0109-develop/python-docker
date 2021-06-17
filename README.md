# python Docker 開発環境

## ●概要
python + Dockerの開発環境です。  

### Dockerファイルについて
```
# 下記内容を変更することでpythonのversionを変更できます。
# デフォルトでは3.8を指定
FROM python:3.8
```

### .envファイルについて
pythonのソースコードの環境パスを設定します。  

### requirements.txtについて
インストールするパッケージを記述します。

## ●使い方

### Dockerコンテナ起動
```
$ docker-compose up -d
```

### 実行
```
$ docker exec -it python3 python sample.py
```

### コンテナ破棄
```
$ docker-compose down
```
