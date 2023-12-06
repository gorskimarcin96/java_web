# Web app

## How to run the app in development

> [!WARNING]
> Project requires **docker-compose**.

### Build app
```sh
docker-compose -f docker/docker-compose-app-builder.yml up
```

### Create .env file
```sh
docker/.env.dist docker/.env
```

### Build and containers
```sh
docker-compose -f docker/docker-compose.yml build
docker-compose -f docker/docker-compose.yml up -d
```
### Run your browser [app](http://localhost:8080/java_web/).
