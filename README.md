# Latest Ionic and git
### based on the latest Cordova with the latest Android and the latest Node.js and the latest Ionic
----
### Pull from Docker Hub
```
docker pull cronos/ionic-git:latest
```

### Build from GitHub
```
docker build -t cronos/ionic-git github.com/Bedotech/docker-ionic
```

### Run image
```
docker run -it cronos/ionic-git bash
```

### Use as base image
```Dockerfile
FROM cronos/ionic-git:latest
```
