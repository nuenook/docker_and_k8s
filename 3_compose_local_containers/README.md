# docker compose 
communication or networking between separate containers
by first create docker-compos.yml

## structure 
version : version of docker-compose

services: type of docker containers...
    
    - redis-server
        
        - make it use redis image

    - node-app

        - make dockerfile to app
        - map port

## docker compose command
    

### docker-compose up 
like docker run myimage

### docker-compose up --build
rebuild that 
 docker build .
 and 
 docker run myimage


### docker-compose up -d 
Launch in background

### docker-compsoe down
Stop Containers

### restart policies
- no
- always
- on-failure
- unless-stopped

### docker-compose ps
same docker ps but looking on current docker-compose.yml only