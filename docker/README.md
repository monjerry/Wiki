* To run a container and use bash immediately
```bash
docker run -i -t ubuntu
```

* To remove all containers
```bash
docker rm $(docker ps -a -q)
```
