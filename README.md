## 起動

```bash
docker-compose up -d
```

## ログ確認

`CONTAINER ID` を確認する

```bash
docker ps

CONTAINER ID        IMAGE               COMMAND                  CREATED             STATUS              PORTS                    NAMES
bd903bea004c        nginx:alpine        "nginx -g 'daemon of…"   3 minutes ago       Up 3 minutes        0.0.0.0:80->80/tcp       codeigniter_web_1
```

```bash
docker attach bd903bea004c
```

## コンテナ接続

`CONTAINER ID` を確認する

```bash
docker exec -it bd903bea004c /bin/sh
```
