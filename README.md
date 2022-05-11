# minecraft-web-nginx

`docker-compose.yml`
```yml
version: '3'

services:

  nginx:
    container_name: nginx
    image: minecraft-web-nginx
    build:
      context: .
      dockerfile: Dockerfile
    ports:
      - 80:80
      - 443:443
      - 25565:25565/tcp
```

## LICENSE
MIT License
