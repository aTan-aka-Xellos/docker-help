# Docker-help  

## Containers  

### Lifecycle  

* [`docker create --name <name> <image-name>`](https://docs.docker.com/engine/reference/commandline/create) creates a container but does not start it.
* [`docker rm <names>`](https://docs.docker.com/engine/reference/commandline/rm) remove one or more containers.

`docker rm $(docker ps -a -q)` remove all stopped containers

### Info  

* [`docker ps -a`](https://docs.docker.com/engine/reference/commandline/ps) shows all (-a) containers.
* [`docker inspect`](https://docs.docker.com/engine/reference/commandline/inspect) looks at all the info on a container (including IP address).
* [`docker port`](https://docs.docker.com/engine/reference/commandline/port) shows public facing port of container.


* [`docker stats --all`](https://docs.docker.com/engine/reference/commandline/stats) display a live stream of container(s) resource usage statistics.

## Images  

### Lifecycle  
* [`docker pull <name>`](https://docs.docker.com/engine/reference/commandline/pull) pulls an image from registry to local machine.
* [`docker rmi <names>`](https://docs.docker.com/engine/reference/commandline/rmi) remove one or more images.

