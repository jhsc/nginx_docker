# nginx_docker
docker-compose with nginx proxy and letsencrypt

### Usage
```
git clone https://github.com/jhsc/nginx_docker
cd nginx_docker
```

Create docker nertworks

```
docker network create traffic_front
docker network create traffic_back
docker-compose up -d
```
