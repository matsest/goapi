# goapi

Testing testing... creating a HTTP REST API server in golang.

Based on https://dzone.com/articles/how-to-write-a-http-rest-api-server-in-go-in-minut
See the original repository: https://github.com/scraly/http-go-server

## Usage

### Build

```
$ make build
```

### Run API server

```
$ ./bin/http-go-server
```

### Test API server

```
$ curl http://localhost:8080/healthz
OK

$ curl http://localhost:8080/hello/mats
"Hello mats!"

### Other

See

`make help`

for more instructions
