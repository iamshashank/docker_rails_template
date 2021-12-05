# Rails Docker bolerplate with Ngnix, Redis, Sidekiq, Postgres support

## Requirement
* Docker Compose

## Useage
```
# to run every process without scale
docker-compose up

# to scale web server to 6 and keep sidekiq process to 1
docker-compose up --scale web=6 --scale worker=1
```
