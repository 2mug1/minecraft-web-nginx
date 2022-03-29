# nginx

`docker-compose.yml`
```yml
version: '3'

services:

  nginx:
    container_name: nginx
    image: ghcr.io/takagi-minecraft-lab/nginx
    ports:
      - 80:80
      - 443:443
      - 25565:25565
```

## LICENSE
MIT License