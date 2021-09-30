# dockercompose-py3-awscli2

The aim of this Dockerfile is to build an image which allows a CI/CD pipeline to run python integration tests for Docker applications with AWS dependencies.

This Dockerfile contains 
 - docker (with dind)
 - docker-compose
 - python v3.8
 - awscli2
 - pytest & pytest-docker

The OS is linux amd64.

Go to [dockerhub](https://hub.docker.com/repository/docker/sassy19a/dockercompose-py3-awscli2/) to download the image.
