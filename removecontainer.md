to remove container we can use

spacific container :

```

docker rm <container_id_or_name>

```

example

```
docker rm my_container

```

for delete all stop contianer

```

docker container prune

or

docker container prune -f

```

Clean everything — all containers, images, volumes, and networks that are unused:

```
docker system prune -a

```
