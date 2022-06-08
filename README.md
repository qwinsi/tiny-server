# Tiny Server

A sample HTTP server written in Golang.

# Building

```shell
go build -o tinyserver  ./src/main.go
```

# Runing

run `./tinyserver --help` to get helpful information.

```shell
$ ./tinyserver --help
 Usage:   tinyserver [OPTIONS] <directory>
 Options: 
    -p, --port The port number which you want to bind on.
                         (If omitted, use 80 by default)
```
