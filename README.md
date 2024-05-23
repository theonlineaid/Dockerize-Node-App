## Node + Docker 

```
docker build -t node-image .
docker run -v ${PWD}:/app -p 7000:7000 -d --name node-container node-image
docker exec -it --name node container bash
```