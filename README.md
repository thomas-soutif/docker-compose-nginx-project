# docker-compose-nginx-project
A project that show 2 api and a front application (react) that is acces with a reverse proxy

This project was develop on a **linux** system. If you want to contenerise it under windows, please modify the volume for the postgres in the docker compose file
## How to build

```bash
docker compose up -d --build
```

## Urls

Front : http://localhost:80

Api1 : http://localhost:80/api1

Api2 : http://localhost:80/api2
