# Docker config Django and postgres Whith Angular

## Requirements

- docker
- docker-compose

## Deploy && Usage

```sh
# build
$ docker-compose up --build

# start
$ docker-compose up -d

# start production
$ docker-compose -f docker-compose-prod.yml up -d --build

# stop
$ docker-compose down

# remove
$ docker-compose down -v
```

### Snapshot
API `http://localhost:8081`
access `http://localhost:8080`
production `http://localhost:80`