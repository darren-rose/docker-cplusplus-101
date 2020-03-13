# docker-cplusplus-101

#### build

build base image
```
docker build -t cpp-build-base -f DockerfileBase .
```

build image
```
docker build -t hello-world -f DockerfileProd .
```

run
```
docker run --rm -it hello-world
```
