# docker-compose
docker-compose
catalogue web:v.0.0.1
user  web:v.0.1.0
cart  web:v.0.1.1
shipping web:v.1.0.0

- docker compose install ubuntu 22.04

```
mkdir -p ~/.docker/cli-plugins/

```

```
curl -SL https://github.com/docker/compose/releases/download/v2.3.3/docker-compose-linux-x86_64 -o ~/.docker/cli-plugins/docker-compose

```

```
chmod +x ~/.docker/cli-plugins/docker-compose
```