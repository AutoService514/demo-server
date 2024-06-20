## Server part for AutoService

## How to start

```bash
$ npm i
```

## Running the app

```bash
# development
$ docker-compose up -d --build
```

## Running the migrations

```bash
$ docker exec -ti <container_name> sh
    # then
$ npm run migration:run
```
