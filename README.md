# Docker Alpine Java NodeJs

## Description

The image is the smallest possible version of Docker container running Java and NodeJS. It's size is 236MB.

The image is ideal to run automated builds in the docker container, like Cordova or React-Native. Just use this image and run commands to build the project.

## Build image

`docker build -t docker-alpine-java_8-nodejs .`

## Start container

`docker run --rm -v $PWD:/data docker-alpine-java_8-nodejs`
