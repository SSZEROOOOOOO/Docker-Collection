# Docker-Collection
 For those services need Rapid deployment

# Create

## Dockerfile
### use Dockerfile in this folder
 docker build -t 'images-name' . 
#### example
 docker build -t ssz7/jupyternb . 

### use Dockerfile on github
 docker build github.com/../..
#### example
 docker build github.com/sszerooooooo/Docker-Collection/jupyter

## docker-compose
### use docker-compose.yml in this folder
 docker-compose up -d

# Inspect
### see all downloaded and own images
 docker image ls -a
### see running containers
 docker container ls
 docker ps

# Delete
## for docker create by Dockerfile
 docker rm -f xxxx
## for docker create by docker-compose.yml
 docker-compose down 
 removes the containers and default network, but preserves your WordPress database.

 docker-compose down --volumes 
 removes the containers, default network, and the WordPress database.

