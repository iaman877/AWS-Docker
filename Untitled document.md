# Docker command line syntax:

* Old: docker <command> options
* New: docker <management command> <command> options

## Default image registry for docker is hub.docker.com

- [x] List docker images:
- old : docker images
- new : docker image ls

- [x] Start Container from docker image centos :
- old : docker run -it centos
- new : docker container run -it centos

- [x] Check list of running containers:
- old : docker ps
- new : docker container ps  or # docker container ls


