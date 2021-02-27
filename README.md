# Base docker configuration for Laravel/Lumen framework
Configuration:
1. Move docker folder to root your project
2. Copy `docker/.env.example` to `docker/.env`
3. Replace `example` on your project name in (docker folder): `docker-compose.yml`, `.env` and `default.conf` files
4. Adding _your_project_name.test_ on host file

## Current structure files
```
project
│   app
│   bootstrap
|   databace
|   docker
|   etc...
```

## Run Project
```bash
cd docker && docker-compose up -d
```
