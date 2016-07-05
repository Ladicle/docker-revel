# Docker Revel

This repository provide Dockerfile for Revel.

## How to build image

1. Setup docker.
1. Run the following command.
```bash
$ docker build -t revel .
```

## How to use image
1. Go to revel application path.
1. Run the following command.
```bash
$ docker run -it --rm -v "$PWD":/go/src/[path-to-repo] -w /go/src/[path-to-repo] revel revel run [path-to-repo]
```
