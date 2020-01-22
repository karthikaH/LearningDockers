# My Learnings on Dockers

Please Find below my comprehensions on the very useful dockers

## Getting Started

Dockers was made based on linux containers

![alt text](./docker-basic.png)

### Frequently used docker commands

*`docker run -it <container-name>` - runs the container interactively
*`docker run <container-name>` - wouldn't hold on to it
*`docker run <flags> <container-name> <all-commands-to-execute>` - Order matters eg: `docker run -it -rm node ls`
*`docker image prune` - clears up the space, but nest time we need to rebuild everything once we pull


