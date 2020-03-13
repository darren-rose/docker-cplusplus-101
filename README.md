# docker-cplusplus-101

#### build

build base image
```
docker build -t cpp-build-base:0.1.0 -f DockerfileBase .
```

build image
```
docker build -t hello-world:1.0.0 -f DockerfileProd .
```

run
```
docker run --rm -it hello-world:1.0.0
```
