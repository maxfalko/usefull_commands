# Basic commands 

## Check current version of docker

```docker --version ```

## Find other options

``` docker --help ```

## Show running containers

``` docker ps```

### Show all containers running & stoped

``` docker ps -a```

## Show container statistics


```dockre stats ```

## Run container


```docker run container_name ```

## Run container in background

```docker run container_name & ```

### other way to run in background

```docker run -d container_name ```

#### r run in background all network interfaces attached to this conteiner

```docker run -P-d container_name ```

## Delete container

```docker rm conatainer_id or name```

## Show container logs 

```docker logs container_id```

## Run bash in container

``` ddocker exec -it container_id /bin/sh```