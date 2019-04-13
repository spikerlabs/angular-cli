# Minimal docker image with angular cli preinstalled.

## Installation ##

1. Install [Docker](https://www.docker.com)
2. Pull [automated build](https://hub.docker.com/r/spikerlabs/angular-cli/) from public [Docker Hub Registry](https://hub.docker.com):
```
docker pull spikerlabs/angular-cli
```
Alternatively, you can build an image from Dockerfile:
```
docker build -t scala-sbt github.com/spikerlabs/angular-cli
```

## Usage ##

```
docker run -it --rm spikerlabs/angular-cli /bin/bash
```
