# docker-percona-toolkit

Alpine Docker image to run [Percona Toolkit commands](https://www.percona.com/doc/percona-toolkit/3.0/index.html].)

[View latest version here](https://www.percona.com/downloads) and set build args accordingly

```sh
$ docker build --build-arg version=3.5.7 -t pto .

# Verify that it runs
$ docker run -it pto pt-online-schema-change --version
> pt-online-schema-change 3.3.1
```
