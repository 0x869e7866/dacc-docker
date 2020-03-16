# DACC-docker

tools for building DACC private network by Docker

## standalone

``` sh
$ cd standalone
$ docker-compose up -d --build
$ docker exec -it gdacc /gdacc attach ipc://root/.dacc/gdacc.ipc
```
