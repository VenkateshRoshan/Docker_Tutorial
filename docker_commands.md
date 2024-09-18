# Docker Commands
### To create an Image
```
docker build -t <image_name> .
```

### To run the Image
```
docker run <image_name>
```

### To tag the Docker Image in Docker Hub
```
docker tag <image_name> username:/repo_name:tag_name
```

### To push into Docker Hub
```
docker push username/repo_name:tag_name
```

### To pull the Docker Image from Docker Hub
```
docker pull username/repo_name:tag_name
```

### To run the pulled Docker Image
```
docker run -d username/repo_name:tag_name
```