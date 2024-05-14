# recipe-app-api
Learning Django

## Running commands inside docker
```shell 
docker-compose run --rm app sh -c "<Command you want to run inside the container>"
```
### Linting command
```shell 
docker-compose run --rm app sh -c "flake8"
```
### Creating project
```shell
docker-compose run --rm app sh -c "django-admin startproject app ."
```

## To run the app

```shell
docker compose up
```
