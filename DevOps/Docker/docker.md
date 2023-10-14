# Docker Cheat Sheet

```shell
docker ps -a # list all containers
```

```shell
docker images # list all images
```

```shell
docker run -it -p 8080:80 nginx # run nginx image on port 8080
```

```shell
docker run -it -p 8080:80 -v $(pwd):/usr/share/nginx/html nginx # run nginx image on port 8080 and mount current directory to nginx html directory
```

