
# build docker 



### run image
```
docker run -it -p 8083:8083 -v ~/Desktop/docker/code:/code images-name
```

### access container
```
docker exec -it containerId bash   
```



### del all dockers
```
docker stop $(docker ps -aq)    
docker rm $(docker ps -aq)    
docker rmi $(docker images -q)   
```

---
# build image of thriveethemeupdate based on ubuntu:16.04
### pull image
```
docker pull ubuntu:18.04
```








