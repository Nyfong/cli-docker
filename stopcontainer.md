to stop all containers we can use this command

```
docker stop $(docker ps -q)
```

this one list all id of running contatiner

```
$(docker ps -q)
```
