# gollum-docker

Dockerfile for gollum

Build the docker container

``` bash
docker build -t gollum .
```

Run gollum in a directory containing the git wiki

``` bash
docker run -v `pwd`:/wiki -p 80:80 gollum
```
