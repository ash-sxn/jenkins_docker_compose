# jenkins_docker_compose
Jenkins docker installation with docker CLI with frequently used blue ocean plugins and features
For macOS and linux system 
use 
```
docker compose up -d 
```
(-d for running in background) 
this will spin up 2 docker container with with docker:dind image to execute docker commands inside Jenkins nodes It can be removed after the process and one container running jenkins on port 8080 and 50000 for communiction between multi container setup
